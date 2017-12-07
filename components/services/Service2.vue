<template>
  <div class="service2">
    <div class="service-text">
      <h2>Service B</h2>
      <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p>
    </div>
    <div class="service-img">
      <p>Image here</p>
    </div>
  </div>
</template>

<style scoped>
.service2 {
  background-color: red;
  display: grid;
  grid-template-columns: 2fr 1fr;
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
