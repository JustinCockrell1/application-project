<script setup>
import Header from '../components/Header.vue'
import GetStarted from '../components/GetStarted.vue'
import Section2 from '../components/Section2.vue'
import Section3 from '../components/Section3.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
  <main>
    <Header image="false"></Header>
  <GetStarted></GetStarted>
  <Section2></Section2>
  <Section3></Section3>
  <Footer></Footer>
  <RouterView />
  </main>
</template>
