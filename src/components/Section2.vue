<script setup>
    import Card from './Card.vue';
</script>

<template>
    <div class="container">
        <img src="../assets/images/ellipse.svg" alt="">
        <h1><b>What We Do</b><br> For Your <span class="underlined">Business</span></h1>
        <Card title="WEBSITE DESIGN" description="Lorem Ipsum has been the industry's standard dummy text ever since the 1500s" color="var(--color-magenta)" image="../assets/images/website-icon.svg"></Card>
        <Card title="WEB DEVELOPMENT" description="Lorem Ipsum has been the industry's standard dummy text ever since the 1500s" color="var(--color-light-orange)"></Card>
        <Card title="MOBILE APP DEVELOPMENT" description="Lorem Ipsum has been the industry's standard dummy text ever since the 1500s" color="var(--color-light-blue)"></Card>
        <Card title="MARKETING" description="Lorem Ipsum has been the industry's standard dummy text ever since the 1500s" color="var(--color-light)"></Card>
    </div>
</template>

<style scoped>

.container{
    margin-top: 150px;
    padding: 50px;
    /* background-color: var(--color-light-blue); */
    background: none;
    text-align: center;
    position: relative;
}

.container::before {
    position: absolute;
    left: 0;
    top: 0;
    content: '';
    width: 90%;
    border-radius: 0 400px 0 0;
    height: 100%;
    background-color: var(--color-light-blue);
}

h1 {
  font-size: 48px;
  line-height: 51px;
  font-weight: normal;
  margin-bottom: 4rem;
}

img {
    position: absolute;
    right: 0;
    top: 20%;
    width: 30%;
    z-index: -1;

}

h1 b {
  font-weight: bold;
}

</style>