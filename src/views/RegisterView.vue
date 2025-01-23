<script setup lang="ts">
import TwoColumns from '../components/TwoColumns.vue'
import ThreeColumns from '../components/ThreeColumns.vue'
</script>

<template>
  <div class="header">
    REGISTER
  </div>

  <div class="form-container">
    <form>
      <fieldset>
        <TwoColumns/>
        <ThreeColumns/>
      </fieldset>

      <input
        type="submit"
        value="Submit"
      />
    </form>
  </div>
</template>

<style scoped>
  .header {
    text-align: center;
    font-size: 50px;
    font-weight: bold;
    padding-top: 80px;
  }

  .form-container {
    padding-top: 50px;
    display: flex;
    justify-content: center;
    min-height: 50vh;
  }

  form {
    width: 50%;
  }
</style>