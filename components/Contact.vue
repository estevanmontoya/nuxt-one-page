<template>
  <div class="contact">
    <div class="content">
      <div class="form">
        <textarea name="name"></textarea><br>
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
  </div>
</template>

<style scoped>
.contact {
  background-color: #f9f9f9;
}
.content {
  display: grid;
  grid-gap: 40px;
}
.form {

}
.contact-info {

}
@media (min-width: 1024px) {
  .content {
    grid-template-columns: 1fr 1fr;
    width:80%;
    margin: auto;
    padding: 100px 40px;
  },
  textarea {
    width:100%;
  }
}
@media (max-width: 300px) {
  .content {
    width: 100%;
    padding: 20px;
  },
  textarea {
    width:100%;
  }
}
</style>
