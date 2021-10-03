<template>
  <div class="container-fluid">
    <Header/>
    <div class="container "><Navbar/></div>
    
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld
    Header,
    Navbar,
  }
}
</script>

<style>
#app {
  font-family: sans-serif, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
