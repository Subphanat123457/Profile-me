<template>
  <div class="container text-center">
    <div class="row">
      <div class="col">
     
      </div>
      <div class="col-6">
        <HelloWorld />
        <Navbar class="m-right" />
        <About />
      </div>
      <div class="col">

      </div>
    </div>
  </div>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    About
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
