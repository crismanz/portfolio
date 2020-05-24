<template>
  <div id="app">
    <Nav/>
    <Hello/>
    <About/>
    <footer id="footer">
      <p>Cristina Manzoni</p>
      <p>&copy; Copyright {{date()}}</p>
    </footer>
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
  },
  methods: {
    date() {
      return new Date().getFullYear();
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

img {
  height: 60px;
}

.container {
  width: 80%;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

#footer {
  position: fixed;
  bottom: 0;
  border-top: 1px solid #dee2e6;
  width: 100%;
  text-align: center;
}
</style>
