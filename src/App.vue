<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">


    <nav class="centre">
      <nav class="navbar navbar-inverse">
        <ul class="nav menu">
          <li>
            <router-link to="/about" @click.native="closeNavBarFromChild">About</router-link>
          </li>
          <li class="hidden-lg hidden-md">
            <router-link to="/product" @click.native="closeNavBarFromChild">Product</router-link>
          </li>
        </ul>
      </nav>
    </nav>
    <button class="allin" @click="click" >Click to select </button><a href="##">load</a>

    <HelloWorld msg="Welcome "/>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'App',
  components: {
    HelloWorld
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
body{
  background-color: bisque;
}
</style>
