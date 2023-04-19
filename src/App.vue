<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import GetStarted from './components/GetStarted.vue'
import Section2 from './components/Section2.vue'
import Section3 from './components/Section3.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <!-- <Header image="false"></Header>
  <GetStarted></GetStarted>
  <Section2></Section2>
  <Section3></Section3>
  <Footer></Footer> -->
  <RouterView />
</template>

<style scoped>


header {
  padding: 1em;
  display: flex;
  /* width: 100%; */
  justify-content: space-between;
}


.title {
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: 24px;
  font-weight: 700;
}



/* .underlined {
  text-decoration: line-through solid var(--color-orange) 50%;
  text-underline-offset: 5rem;
  line-height: 0;
} */
.underlined {
  text-decoration: none;
  position: relative;
  background: none;
}

.underlined::after{
    content: '';
    width: 100%;
    position: absolute;
    right: 0;
    top: calc( 50% - 1.5px );
    border-bottom: 3px solid rgba(255,0,0,0.8);
}

.description h1 b {
  font-weight: bold;
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
}
</style>
