<template>
  <div class="about">
    <div class="about-text">
      <h3>About our company</h3>
      <p>Bacon ipsum dolor amet nisi adipisicing boudin, chicken cupim ribeye strip steak meatloaf qui nostrud chuck ut bresaola id dolor. Doner ball tip pancetta strip steak nostrud. Boudin eu in beef consequat incididunt sunt doner laboris pig reprehenderit. Lorem jerky pastrami, occaecat cupim aliqua labore tongue ex esse. Occaecat meatloaf landjaeger venison, capicola drumstick sausage pork belly tri-tip proident frankfurter ut. Beef ribs pariatur voluptate frankfurter flank.</p>
    </div>
    <div class="about-image">
      <img src="../assets/manwithfish.jpg" alt="">
    </div>
  </div>
</template>

<style lang="css">
@media (min-width: 1024px) {
  .about {
    grid-template-columns: 3fr 1fr;
  }
}
.about {
  background-color: white;
  display: grid;
}
.about-text {
  padding: 100px 60px;
}
.about-image {
  background-color: grey;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}
.about-image img {
  width:100%;
  height: auto;
}
</style>
