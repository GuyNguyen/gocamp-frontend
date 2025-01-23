<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import logo from './assets/logo.jpg'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <ul>
          <li><RouterLink to="/"><img :src="logo"></RouterLink></li>
        </ul>
        <ul>
          <li><RouterLink to="/about">About</RouterLink></li>
          <li><RouterLink to="/register"><button>Register Now</button></RouterLink></li>
        </ul>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  overflow: hidden;
  padding-right: 25px;
  border-bottom: 1px solid #e2514e33;
  width: 100%;
  text-align: center;
}

img {
  width: 90px;
  height: auto;
}


</style>
