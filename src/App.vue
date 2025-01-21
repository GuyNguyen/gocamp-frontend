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
          <li><RouterLink to="/about"><button>About</button></RouterLink></li>
        </ul>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  overflow: hidden;
  /* padding-left: 20px; */
  padding-right: 30px;

  width: 100%;
  text-align: center;
}

img {
  width: 128px;
  height: auto;
}


</style>
