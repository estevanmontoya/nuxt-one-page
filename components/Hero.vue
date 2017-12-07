<template>
  <div class="hero">
    <div class="content">
      <h1>Hero Text</h1>
      <h2>Sub Title Text Goes Here</h2>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped lang="css">
.hero {
  width: 100%;
  margin: 0px auto;
  padding: 200px 0px;
  background-image: url('./../assets/flyfishing.jpg');
  background-position: bottom center;
  background-size: cover;
}
.content {
  text-align: center;
  color: white;
}
h2 {
  font-size: 20px;
  letter-spacing: 10px;
}
@media (min-width: 1024px) {
  .hero {
    background-position: center left;
  }
}
</style>
