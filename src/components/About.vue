<template>
  <div id="about" class="container">
    <div class="about">
      <h2>Hi there, I'm Cristina.</h2>
      <p>I'm a Full-stack developer and I love to create new stuff.
        I have about 2 years of work experience and I plan on growing in the years to come.</p>
      <p>I'm hard working and love working on projects, as individual or in a team, big or small, especially when they push me to my limits.</p>
      <p>If I'm not in front of the screen you can find me outside hiking on mountain peaks or in the ocean catching some waves.</p>
      <br><p>Want to talk about coding or anything else?!</p>
      <p>Let's get in touch!</p>
      <div class="logos">
        <a href="https://www.linkedin.com/in/cristina-manzoni-34254411a/" target="_blank"><img src="../assets/linkedin_logo.png"></a>
        <a href="https://github.com/crismanz" target="_blank"><img src="../assets/github_logo.png"></a>
        <a href="mailto:someone@example.com"><img src="../assets/mail_logo.png"></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style scoped>
.about {
  text-align: left;
}

.logos a {
  margin: 10px;
  height: 40px;
}

img {
  height: 40px;
}
</style>
