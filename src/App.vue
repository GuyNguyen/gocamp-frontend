<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <ul>
          <li><RouterLink to="/">Hono Go Club</RouterLink></li>
        </ul>
        <ul>
          <li><RouterLink to="/about">About</RouterLink></li>
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
    padding-left: 20px;
    padding-right: 20px;

    width: 100%;
    text-align: center;
  }


</style>
