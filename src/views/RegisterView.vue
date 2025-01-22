<script setup lang="ts">

</script>

<template>
  <div class="header">
    REGISTER
  </div>

  <div class="form-container">
    <form>
      <fieldset>
        <label>
          Name
          <input
            name="name"
            placeholder="Your name"
            autocomplete="given-name"
          />
        </label>
        <label>
          Phone
          <input
            name="phone"
            placeholder="Your Phone"
            autocomplete="tel-national"
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
        value="Submit"
      />
    </form>
  </div>
</template>

<style scoped>
  .header {
    text-align: center;
    font-size: 50px;
  }

  .form-container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 50vh;
  }

  form {
    width: 350px;
  }
</style>