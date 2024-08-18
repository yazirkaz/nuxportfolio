<template>
  <div class="container">
    <nav>
      <img src="/assets/Asim Yazir.png" class="logo">
      <ul>
        <li><a href="#header">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="header-text">
      <h1>Hi, I'm <span>YAZIR</span><br> from Marawi</h1>
      <p>Computer Science Student</p>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.images{
  position: relative;
  top: 3rem; /* Adjust the percentage to resize the image */
  width: 32vw; /* Maintain the aspect ratio */ /* Center the image */
}
/* Your styles here */
</style>
