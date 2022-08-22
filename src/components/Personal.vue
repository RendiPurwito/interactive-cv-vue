<script setup>
  defineProps({
    msg: {
      type: String,
      required: true
    }
  })
</script>

<template>
  <div class="greetings">
    <h2 class="green">{{ msg }}</h2>
    <h4>Web Developer</h4>
    <h6>A high school student in computer engineering. I have several programming language skills, interested to working in the IT field for the position of Web Developer</h6>
    <hr>
    <div class="contacts">
      <p>Email : rendipurwito@gmail.com</p>
      <p>Phone : +6281297096073</p>
      <p>Github : RendiPurwito</p>
      <p>Address : Jl. Tunas Karsa No.56, RT 03/RW 06, Sukamaju Baru, Kec. Tapos, Kota Depok, Jawa Barat 16455</p>
    </div>
  </div>
</template>

<style>
  .contacts {
    line-height: 0.5rem;
  }
</style>