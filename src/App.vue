<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <div style="font-size: 200px"> -->
   <!--    ONS KAN MORE VERDER WERK -->
   <!--  </div> -->
    <login></login>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

import Login from "./components/Login";

export default {
  name: 'App',
  components: {
    Login
    //HelloWorld
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
