<template>
  <div class="container text-center">
        <HelloWorld />
        <Navbar class="m-right" />
        <About />
        <Variant /> 
  </div>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import About from './components/About.vue'
import Variant from './components/Variant.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    About,
    Variant
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
