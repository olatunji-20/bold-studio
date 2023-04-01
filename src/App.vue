<template>
  <div>
    <Navbar />
    <Clients />
    <Featured />
    <Footbar />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Clients from './components/Clients.vue'
import Featured from './components/Featured.vue'
import Footbar from './components/Footbar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Clients,
    Featured,
    Footbar
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
