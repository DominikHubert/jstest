<template>
  <div class="bg-gray-600 text-white w-1/2 m-auto mt-12">
    <div class="text-center border-b-2 border-black py-4">
      <h1 class="text-3xl py-4">Unsere ToDos</h1>
      <h1 class="text-xl">Offene ToDos:{{ todos.length }}</h1>
    </div>
    <ToDo/>
  </div>
</template>

<script>
import ToDo from './components/ToDo.vue'

export default {
  name: 'App',
  data(){
    return{
      todos:[
        {todo: "Einkaufen", done: false},
      ],
    };
  },
  components: {
    ToDo
  }
}
</script>

