<template>
  <div class="testimonials">
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
</template>

<script>
export default {
}
</script>

<style lang='css'>
@media (min-width: 1024px) {
  .testimonials {
    grid-template-columns: 1fr 1fr 1fr;
  }
}

.testimonials {
  margin: auto;
  width: 80%;
  display: grid;
  padding: 100px 0px;
  grid-gap: 40px;
}
/*.testimony {
  width: 30%;
}*/
</style>
