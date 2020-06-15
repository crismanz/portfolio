<template>
  <div id="contact" class="container">
    <h2>Let's talk.</h2>
    <div class="contact">
      <div class="socialMedia">
        <p>I would be happy to hear from you.</p>
        <p>Check out my social media or drop me a message.</p>
      </div>
      <form name="contact" method="POST" class="contactForm">
        <input type="text" name="name" placeholder="your name"/>
        <input type="text" name="email" placeholder="email address"/>
        <input type="text" name="subject" placeholder="subject"/>
        <textarea type="text" name="message" placeholder="message" row="3"/>
        <button>Submit</button>
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

.contactForm {
  display: flex;
  flex-direction: column;
}
</style>
