<template>
  <div>
    <!-- <Header /> -->
    <About />
    <Services />
    <Portfolio />
    <Contact />
  </div>
</template>

<script>
import Header from '~/components/Header.vue';
import About from '~/components/About.vue';
import Services from '~/components/Services.vue';
import Portfolio from '~/components/Portfolio.vue';
import Contact from '~/components/Contact.vue';

export default {
  components: {
    Header,
    About,
    Services,
    Portfolio,
    Contact
  }
}
</script>

<style scoped>
/* Add global styles if necessary */
</style>