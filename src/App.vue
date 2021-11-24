<template>
  <div id="app">
    <Users />
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
    <MyComponent />
  </div>
</template>

<script>

import Home from './components/Home.vue'
import MyComponent from './components/MyComponent.vue'
import Users from './components/Users.vue'
export default {
  name: 'App',
  components: {
     Home, MyComponent, Users //Register
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
