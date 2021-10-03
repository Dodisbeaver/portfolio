<template>
  <div class="container-fluid">
    <div class="container">
        <HeaderText/>
    </div>
    
    <div class="container "><Navbar/></div>
    <div class="container">
      <div class="row">
         <WorkExperience/>
          <Skills/>
      </div>
     
    </div>
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderText from './components/HeaderText.vue'
import Navbar from './components/Navbar.vue'
import WorkExperience from './components/WorkExperience.vue'
import Skills from './components/Skills.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderText,
    Navbar,
    WorkExperience,
    Skills,
  }
}
</script>

<style>
#app {
  font-family: sans-serif, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
