<template>
  <div id="app">
    <nav>
      <li><a href='#app'>Cristina Manzoni</a></li>
    </nav>
    <img alt="wave" src="./assets/wave.svg">
    <Hello/>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'

export default {
  name: 'App',
  components: {
    Hello
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

img {
  height: 60px;
}
</style>
