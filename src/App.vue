<template>
  <div>
    <Top />
    <Clients />
    <Featured />
    <Services />
    <Footbar />
  </div>
</template>

<script>
import Top from './components/Top.vue'
import Clients from './components/Clients.vue'
import Featured from './components/Featured.vue'
import Services from './components/Services.vue'
import Footbar from './components/Footbar.vue'

export default {
  name: 'App',
  components: {
    Top,
    Clients,
    Featured,
    Services,
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
