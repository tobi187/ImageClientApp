<template>
<div class="bg-gradient-to-r from-purple-500 to-pink-500 h-screen">
  <HomePage msg="Welcome to Your Vue.js App"/>
</div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import HomePage from "./components/HomePage.vue"

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
