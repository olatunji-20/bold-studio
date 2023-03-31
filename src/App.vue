<template>
  <div>
    <Navbar />
    <Clients />
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Clients from './components/Clients.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Clients,
    HelloWorld
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}
body {
    margin: 0px !important;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
