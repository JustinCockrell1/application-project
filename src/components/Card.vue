<script setup>

</script>

<template>
<div class="card">
    <!-- <img src="../assets/images/website-icon.svg" :style="{background:color}"> -->
    <!-- <img :src="{image}" alt=""> -->
    <div :style="{backgroundImage: `url(${image})`}"></div>
    {{ image }}
<div class="title">
    {{ title }}
</div>
<div class="description">
    {{ description }}
</div>
</div>

</template>

<style scoped>

.card {
    width: 290px;
    height: 192px;
    border-radius: 10px;
    background-color: white;
    display: inline-block;
    margin:0 20px;
    margin-bottom: 20px;
    box-shadow: 0px 0px 9px 2px rgba(0, 0, 0, 0.05);
    text-align: left;
    padding: 15px;
}

.title {
    font-size: 16px;
    font-weight: 700;
}

.description {
    font-size: 14px;
    font-weight: 400;
}  

img {
    background-color: var(--color-magenta);
    border-radius: 10px;
}

.red {
    color: red !important;
}

</style>

<script>
export default {
    props: {
        title: String,
        description: String,
        color: String,
        image: String
        
    }
}
</script>