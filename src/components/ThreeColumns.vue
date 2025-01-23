<script setup lang="ts">
import States from '../components/States.vue';
</script>

<template>
  <div class="grid">
    <label>
      City *
      <input
        name="city"
        placeholder="City"
        autocomplete="address-level2"
      />
    </label>
    <label>
      Address *
      <input
        name="address"
        placeholder="Address"
        autocomplete="street-address"
      />
    </label>
    <label>
      State *
      <States/>
    </label>
  </div>
</template>

<style scoped>

</style>
