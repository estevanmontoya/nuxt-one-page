<template>
  <div class="testimonials">
    <h2>What others are saying</h2>
    <div class="content">
      <div class="testimony">
        <h3>Name</h3>
        <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p>
      </div>
      <div class="testimony">
        <h3>Name</h3>
        <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p>
      </div>
      <div class="testimony">
        <h3>Name</h3>
        <p>Bacon ipsum dolor amet cillum cupidatat chuck, ut in minim chicken beef ribs shoulder. Kevin ullamco nisi ground round cillum burgdoggen meatball culpa tri-tip aute.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped lang='css'>
.testimonials {
  margin: auto;
  background-color: #f9f9f9;
  padding: 20px;
  text-align: center;
}
h2 {
  margin-bottom: 40px;
}
.content {
  display: grid;
  grid-gap: 40px;
}
.testimony {
  text-align: center;
  background-color: white;
  border-radius: 20px;
  padding: 20px;
  box-shadow: 0px 10px 10px rgba(0,0,0,.05);
  margin: 0px;
}
.testimony h3 {
  font-size: 16px;
}
.testimony p {
  font-weight: 100;
  font-size: 16px;
}
@media (min-width: 1024px) {
  .testimonials {
    padding: 60px;
  },
  .content {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
</style>
