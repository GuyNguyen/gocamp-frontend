<script setup lang="ts">
</script>

<template>
  <div class="grid">
    <label>
      Name
      <input
        name="name"
        placeholder="Your name"
      />
    </label>
    <label>
      Phone
      <input
        name="phone"
        placeholder="Your phone"
        autocomplete="tel-national"
      />
    </label>
  </div>
</template>

<style scoped>
  .grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: auto;
  }
</style>
