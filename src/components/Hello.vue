<template>
  <div id="hello" class="container">
    <div>
      <h3>Hello everyone,</h3>
      <h1>I'm a Full-Stack <br>Developer</h1>
    </div>
    <img alt="wave" src="../assets/wave.svg">
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
#hello {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  text-align: left;
  margin-top: 20px;
}
h3 {
  margin: 40px 0 0;
}

img {
  height: 280px;
}
</style>
