<template>
  <div id="hello" class="container">
    <img alt="wave" src="../assets/wave.svg">
    <h3>Hello everyone,</h3>
    <h1>I'm a Full-Stack Developer</h1>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
