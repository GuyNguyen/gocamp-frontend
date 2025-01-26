<script setup lang="ts">
</script>

<template>
  <div class="footer">
    <div class="footer-content">
      <div class="footer-left-content">
        <h2>Contact</h2>
        <h5>Phone</h5>
        <a class="link-footer" href="tel:(808)555-0120">(808)555-0120</a> <br>
        <a class="link-footer" href="tel:(808)555-0116">(808)555-0116</a>
      </div>

      <div class="footer-right-content">
        <h2>LET'S GET IN TOUCH</h2>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding-top: 50px;
    position: relative;
  }

  .footer-content {
    display: flex;
    width: 100%;
  }

  .footer-left-content {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
    width: 50%;
    padding-top: 50px;
  }

  .footer-right-content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 60%;
    padding-top: 50px;
  }
</style>
