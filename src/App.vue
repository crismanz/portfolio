<template>
  <div id="app">
    <Nav/>
    <Hello/>
    <About/>
    <Skills/>
    <Contact/>
    <footer id="footer">
      <p><a href="#hello">Cristina Manzoni</a> &copy; Copyright {{date()}}</p>
    </footer>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Hello from './components/Hello.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Hello,
    About,
    Skills,
    Contact
  },
  methods: {
    date() {
      return new Date().getFullYear();
    }
  }
}
</script>

<style>
#app, button {
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: larger;
  color: #2c3e50;
}

::-webkit-input-placeholder { /* WebKit, Blink, Edge */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
:-moz-placeholder { /* Mozilla Firefox 4 to 18 */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
::-moz-placeholder { /* Mozilla Firefox 19+ */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
:-ms-input-placeholder { /* Internet Explorer 10-11 */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
::-ms-input-placeholder { /* Microsoft Edge */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

::placeholder { /* Most modern browsers support this now. */
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.container {
  width: 80%;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
  padding-bottom: 40px;
}

#footer {
  position: relative;
  bottom: 0;
  border-top: 1px solid #dee2e6;
  width: 100%;
  text-align: center;
}

#footer a {
  font-weight: 600;
}

a {
  text-decoration: none;
  color:royalblue;
}

p {
  line-height: 2;
}

h2 {
  color:royalblue;
  border-bottom: 2px solid royalblue;
}
</style>
