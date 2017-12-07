<template>
  <div class="service3">
    <div class="service-img">
      <p>Image here</p>
    </div>
    <div class="service-text">
      <h2>Service C</h2>
      <p><h3>Name</h3>
      <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p></p>
    </div>
  </div>
</template>

<style scoped>
@media (min-width: 1024px) {
  .service3 {
    grid-template-columns: 1fr 2fr;
  }
}
.service3 {
  background-color: darkgreen;
  display: grid;
  height: 400px;
}
.service-img {
  background-color: grey;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}
.service-text {
  color: white;
  padding: 40px;
}
</style>
