<template>
  <div id="app">
    <Nav/>
    <Hello/>
    <About/>
    <Skills/>
    <footer id="footer">
      <p><a href="#hello">Cristina Manzoni</a></p>
      <p>&copy; Copyright {{date()}}</p>
    </footer>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Hello from './components/Hello.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Hello,
    About,
    Skills
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

a {
  text-decoration: none;
}
</style>
