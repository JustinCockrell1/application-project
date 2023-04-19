<script setup>

</script>

<template>
<div class="container">
    <span class="title">Dream Agency</span>

    <div class="box">
    <div class="description">
        <p>
            Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries.
        </p>
    </div>
    <div class="get-in-touch">
        <div class="get-in-touch-text">GET IN TOUCH</div>
        <button>REQUEST MORE INFORMATION</button>
    </div>

</div>
<div class="copyright">
    &copy; {{ new Date().getFullYear() }} Dream Agency, Inc. All right reserved | Privacy Policy | Terms of Use
</div>
</div>
</template>

<style scoped>
.container {
    padding: 2rem 3rem;
    position: relative;
    color: white;
    padding-bottom: 3px;
}

.box {
    display: flex;
}

.get-in-touch {
    margin-left: 100px;
}

.get-in-touch-text {
    font-size: 18;
    font-weight: 700;
   
}

.container::before {
    position: absolute;
    left: 0;
    top: 0;
    content: '';
    width: 100%;
    border-radius: 0 128px 0 0;
    height: 100%;
    background-color: var(--color-black);
}

.description {
    width: 30%;
}



.title {
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: 36px;
  font-weight: 700;

}

p {
  font-weight: 400;
  font-size: 16px;
  margin-bottom: 30px;
}

button {
  margin-top: 15px;
  border-radius: 8px;
  padding: 12px 32px;
  background-color: var(--color-orange);
  color: var(--color-black);
  font-size: 16px;
  font-weight: 700;
}

.copyright {
    text-align: center;
    font-size: 14px;
}
</style>