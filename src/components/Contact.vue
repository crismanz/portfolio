<template>
  <div id="contact" class="container">
    <h2>Let's talk.</h2>
    <div class="contact">
      <div class="socialMedia">
        <p>I would be happy to hear from you.</p>
        <p>Check out my social media or drop me a message.</p>
        <div class="logos">
          <a href="https://www.linkedin.com/in/cristina-manzoni-34254411a/" target="_blank"><img src="../assets/linkedin_logo.png"></a>
          <a href="https://github.com/crismanz" target="_blank"><img src="../assets/github_logo.png"></a>
          <a href="mailto:someone@example.com"><img src="../assets/mail_logo.png"></a>
        </div>
      </div>
      <form name="contact" method="POST" class="contactForm">
        <input type="text" name="name" placeholder="your name" required/>
        <input type="text" name="email" placeholder="email address" required/>
        <input type="text" name="subject" placeholder="subject" />
        <textarea type="text" name="message" placeholder=" message" row="3"/>
        <button disabled>Submit</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style scoped>
.contact {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.socialMedia {
  text-align: left;
}

.logos a {
  margin: 10px;
  height: 40px;
}

img {
  height: 40px;
}

.contactForm {
  display: flex;
  flex-direction: column;
}

.contactForm input {
  margin-bottom: 10px;
}

.contactForm button {
  margin: 10px;
}
</style>
