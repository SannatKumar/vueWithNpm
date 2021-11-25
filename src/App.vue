<template>
  <div id="app">
    <header class="header">
      <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#news">News</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a href="#about">About</a></li>
      </ul>
      <Users />
      <BindClassAndStyle />
    </header >   
    <Home data="Raj is here" msg="message is here"/>
    <MyComponent />
  </div>
</template>

<script>

import Home from './components/Home.vue'
import MyComponent from './components/MyComponent.vue'
import Users from './components/Users.vue'
import BindClassAndStyle from './components/BindClassAndStyle.vue'
export default {
  name: 'App',
  components: {
     Home, MyComponent, Users, BindClassAndStyle //Register
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
.header{
  padding-top: 0px;
  margin-top: 0px;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}
.active {
  background-color: #04AA6D;
}
</style>
