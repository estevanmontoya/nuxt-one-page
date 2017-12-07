<template>
  <div class="contact">
    <div class="form">
      <textarea name="name" rows="8" cols="80"></textarea><br>
      <input type="text" placeholder="Name">
      <input type="email" placeholder="E-Mail"><br>
      <button>Send</button>
    </div>
    <div class="contact-info">
      <h2>Business Name</h2>
      <h3>Contact Name</h3>
      <p>Phone: (123) 456-7890</p>
      <p>
        12345 Long Stree Name<br>
        City Name Here, ST 12345
      </p>
    </div>
  </div>
</template>

<style scoped>
.contact {
  margin: auto;
  width:80%;
  padding: 100px 40px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 40px;
}
.form {

}
.contact-info {

}
</style>
