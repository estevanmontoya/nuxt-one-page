<template>
  <div class="services">
    <service1/>
    <service2/>
    <service3/>
  </div>
</template>

<script>
import Service1 from './services/Service1.vue'
import Service2 from './services/Service2.vue'
import Service3 from './services/Service3.vue'

export default {
  components: {
    Service1,
    Service2,
    Service3
  }
}
</script>
