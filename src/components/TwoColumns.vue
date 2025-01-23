<script setup lang="ts">
</script>

<template>
  <div class="grid">
    <label>
      First Name *
      <input
        name="first_name"
        placeholder="Your first name"
        autocomplete="given-name"
      />
    </label>
    <label>
      Last Name *
      <input
        name="last_name"
        placeholder="Your flast name"
        autocomplete="family-name"
      />
    </label>
    <label>
      Email *
      <input
        type="email"
        name="email"
        placeholder="Email"
        autocomplete="email"
      />
    </label>
    <label>
      Phone *
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
