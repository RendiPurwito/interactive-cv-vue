<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Personal from './components/Personal.vue'
import Footer from './components/Footer.vue'
import Menu from './components/Menu.vue'
</script>

<template>
<!-- Navbar -->
  <!-- <nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="@/assets/logo.svg" alt="" width="30" height="24">
    </a>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active text-white" aria-current="page" href="/">Personal</a>
        </li>

        <li class="nav-item ">
          <a class="nav-link text-white" href="/skill">Skills</a>
        </li>
      </ul>
    </div>
  </div>
  </nav> -->

  <header>
    <!-- <img alt="Foto" class="img-circle" src="@/assets/Foto CV.png" width="150"/> -->
    <div class="image"></div>
    <div class="wrapper">
      <Personal msg="Rendi Purwito Armin" />
    </div>
  </header>

  <Menu />
  <RouterView />
  <Footer />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  padding: 3rem;
  border: 1px solid black;
  border-radius: 20px;
  margin: 50px 100px;
}

.image {
  display: block;
  margin: 0 auto 2rem;
  border: 1px solid black;
  width: 270px;
	height: 170px;
  background-image: url('@/assets/Foto CV.png');
  background-size: cover;
  background-position: center center;
  /* background-color: #0062bd; */
  border-radius: 50%;
  /* box-shadow: 5px 1px 15px  black; */
}

nav {
  background-color: #0062bd;
}
/* nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
} */

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

/* nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
} */

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .image {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    place-items: flex-start;
    flex-wrap: wrap;
  }

  /* nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  } */

}
</style>
