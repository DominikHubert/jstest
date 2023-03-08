<template>
  <div id="app">
    <ToDo msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import ToDo from './components/ToDo.vue'

export default {
  name: 'App',
  components: {
    ToDo
  }
}
</script>

