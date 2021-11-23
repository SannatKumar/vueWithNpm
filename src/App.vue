<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">    
    <Home data="Raj is here" msg="message is here"/>
    <img alt="Vue logo" src="./assets/logo.png">    
    <Home data="Raj is here" msg="message is here"/>
    <img alt="Vue logo" src="./assets/logo.png">    
    <Home data="Raj is here" msg="message is here"/>
    <img alt="Vue logo" src="./assets/logo.png">    
    <Home data="Raj is here" msg="message is here"/>
    <img alt="Vue logo" src="./assets/logo.png">    
    <Home data="Raj is here" msg="message is here"/>
  </div>
</template>

<script>

import Home from './components/Home.vue'
export default {
  name: 'App',
  components: {
     Home //Register
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
