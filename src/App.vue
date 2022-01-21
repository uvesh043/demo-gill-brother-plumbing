<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from "./views/Home.vue";
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  /* color: #2c3e50; */
  /* margin-top: 60px; */
  margin: 0;
}
* { margin: 0 !important; }
</style>
