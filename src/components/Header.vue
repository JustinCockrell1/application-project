<script setup>
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>
  <header>
    
    <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->
    <span class="title">
      Dream Agency

    </span>

    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About Us</RouterLink>
      <RouterLink to="/services">Services</RouterLink>
      <RouterLink to="/contact">Contact Us</RouterLink>
    </nav>
    <!-- <img src="{{ image ? '../assets/images/home-header-graphics.webp' : '../assets/images/home-header-graphics.webp' }}" alt=""> -->
    <img src="../assets/images/home-header-graphics.webp" alt="">
  </header>
</template>


<style scoped>

header {
  padding: 1rem;
  display: flex;
  /* width: 100%; */
  justify-content: space-between;
}

.title {
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: 24px;
  font-weight: 700;
}

header img {
  position: absolute;
  right: 0;
  top: 0;
  z-index: -1;
  width: 40%;
}

nav a {
  margin-left: 20px;
  font-size: 16px;
  font-weight: 700;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
}




</style>

<script>
export default {
    props: {
        image: Boolean
    }
}
</script>