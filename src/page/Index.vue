<template>
    <div class="text-center margin-0">
            <Navbar class="m-right" />
            <About id="#scrollspyHeading1" />
            <concept id="#scrollspyHeading2" />
            <Certificate id="#scrollspyHeading3" />
            <Skill id="#scrollspyHeading4" />
    </div>
    
  </template>
  
  <script>
    import Navbar from '../components/Navbar.vue'
    import About from '../components/About.vue'
    import Concept from '../components/Concept.vue'
    import Certificate from '../components/Certificate.vue'
    import Skill from '../components/Skill.vue'

  export default {
    name: 'App',
    components: {
      Navbar,
      About,
      Concept,
      Certificate,
      Skill,
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
    margin-left: 0px;
    margin-right: 0px;
  }
  
  </style>
  