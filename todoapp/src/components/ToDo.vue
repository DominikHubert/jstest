<template>
  <div class="hello">
    <h1>{{message.toUpperCase()}}</h1>
    <h1>{{ count }}</h1>
    <button v-on:click="countUp">Hochzählen</button>
    <button @click="countDown">Runterzählen</button>
  </div>
</template>

<script>
export default {
  name: 'ToDo',
  data: function () {
    return {
      message: "Hello World!",
      count: 0,
    }
  },
  methods:{
    countUp(){
      this.count++;
    },
    countDown(){
      this.count--;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
