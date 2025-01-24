<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import logo from './assets/logo.jpg';
import Footer from './components/Footer.vue';
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
  <Footer/>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  overflow: hidden;
  padding-left: 30px;
  border-bottom: 1px solid rgb(1, 127, 192);
  width: 100%;
  text-align: center;
}

nav li {
   margin-right: 50px;
   list-style: none;
   text-decoration: none;
   display: inline;
}

img {
  width: 90px;
  height: auto;
}

</style>
