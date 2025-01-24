<script setup lang="ts">
</script>

<template>
  <div class="home">
    <h1>Welcome to the <br><span class="blue-text">Honolulu Go Camp!</span></h1>
    <div class="about-button">
      <RouterLink to="/about"><button class="outline">About Camp</button></RouterLink>
    </div>
  </div>


</template>

<style scoped>
  .home {
    display: flex;
    position: relative;
    flex-direction: column;
    justify-content: center;

  }

  h1 {
    padding-top: 10vh;
    text-align: center;
    color: rgb(6, 30, 47);
    font-size: 100px;
    flex-wrap: wrap;
  }

  .about-button {
    display: flex;
    padding-top: 50px;
    justify-content: center;
  }

  .blue-text {
    color: rgb(1, 127, 192);
  }
</style>