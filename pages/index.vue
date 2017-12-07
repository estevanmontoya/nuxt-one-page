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
  /*min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;*/
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
