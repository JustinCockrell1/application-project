<script setup>

</script>

<template>
    <div class="container">
        <div class="image-container">
    <img src="../assets/images/about-graphics.webp" alt="">
</div>
<div class="content">
    <h1><b>About Us</b><br> Fake or <span class="underlined">Real</span></h1>
    <p>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
    <p>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
    <button>EXPLORE MORE</button>
</div>
</div>
</template>

<style scoped>
.container {
    width: 100%;
    margin-top: 200px;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;

}

/* .img-container {
    width: 30%;
    text-align: center;
    align-items: center;
    border: 5px solid black;
} */

/* img {
    width: 30%;
} */

.content {
    width: 40%;
    margin-left: 30px;
}

h1 {
  font-size: 48px;
  line-height: 51px;
  font-weight: normal;
  margin-bottom: 2rem;
}

p {
  font-weight: 400;
  font-size: 17px;
  margin-bottom: 30px;
}


h1 b {
  font-weight: bold;
}

button {
  border-radius: 8px;
  padding: 12px 32px;
  background-color: var(--color-black);
  color: #FFF;
  font-size: 16px;
}

</style>