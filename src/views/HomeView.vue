<script setup lang="ts">
</script>

<template>
  <div class="form-container">
    <form>
    <fieldset>
      <label>
        First Name
        <input
          name="first_name"
          placeholder="First name"
          autocomplete="given-name"
        />
      </label>
      <label>
        Email
        <input
          type="email"
          name="email"
          placeholder="Email"
          autocomplete="email"
        />
      </label>
    </fieldset>

    <input
      type="submit"
      value="Subscribe"
    />
  </form>
  </div>
</template>

<style>
  .form-container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 80vh;
  }

  form {
    width: 350px;
  }
</style>