<template>
  <div class="container">
    <hero/>
    <about/>
    <testimonials/>
    <services/>
    <contact/>
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue'
import About from '~/components/About.vue'
import Testimonials from '~/components/Testimonials.vue'
import Services from '~/components/Services.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
    Hero,
    About,
    Testimonials,
    Services,
    Contact
  }
}
</script>

<style>
.container {
  width: 100%;
  box-shadow: 0px 0px 60px rgba(0,0,0,.25);
}
@media (min-width: 1024px) {
  .container {
    grid-template-columns: 1fr 2fr;
    max-width: 1440px;
    width: 80%;
    margin: auto;
  }
}

h1, h2, h3, h4, h5, h6 {
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 2px;
}
h1 {
  font-size: 60px;
}
h2 {
  font-size: 45px;
}
h3 {
  font-size: 30px;
}
p {
  font-size: 20px;
}
</style>
