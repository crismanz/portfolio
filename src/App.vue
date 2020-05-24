<template>
  <div id="app">
    <Nav/>
    <Hello/>
    <About/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Hello from './components/Hello.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Hello,
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
}

img {
  height: 60px;
}
</style>
