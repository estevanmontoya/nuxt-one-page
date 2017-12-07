<template>
  <div class="service1">
    <div class="service-img">
      <p>Image here</p>
    </div>
    <div class="service-text">
      <h2>Service A</h2>
      <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p>
    </div>
  </div>
</template>

<style scoped>
.service1 {
  background-color: black;
  display: grid;
  grid-template-columns: 1fr 2fr;
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
