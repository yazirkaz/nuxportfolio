<template>
  <div id="contact">
    <div class="container">
      <div class="row">
        <div class="contact-left">
          <h1 class="sub-title">Contact me</h1>
          <p><i class="fa-solid fa-paper-plane"></i> kasimyazir@gmail.com</p>
          <p><i class="fa-solid fa-phone"></i> 09091784506</p>
          <div class="social-icons">
            <a href="https://web.facebook.com/yzrkz"><i class="fa-brands fa-facebook"></i></a>
            <a href="https://twitter.com/HIROGEXD"><i class="fa-brands fa-x-twitter"></i></a>
            <a href="https://www.instagram.com/y4z3r.0"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://github.com/yazirkaz"><i class="fa-brands fa-github"></i></a>
          </div>
          <a href="images/Resume.pdf" download class="btn btn2">Download CV</a>
        </div>
        <div class="contact-right">
          <form name="submit-to-google-sheet">
            <input type="text" name="Name" placeholder="Your Name" required>
            <input type="email" name="Email" placeholder="Your Email" required>
            <textarea name="Message" row="6" placeholder="Your Message"></textarea>
            <button type="submit" class="btn btn2">Submit</button>
          </form>
          <span id="msg"></span>
        </div>
      </div>
    </div>
    <div class="copyright">
      <p>Copyright © Yazir Kasim with CICS♥ </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style scoped>
/* Add your specific styles for Contact here */
</style>