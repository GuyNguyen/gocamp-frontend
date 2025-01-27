<script setup lang="ts">
import TwoColumnsFooter from './TwoColumnsFooter.vue'
</script>

<template>
  <div class="footer">
    <div class="footer-content">
      <div class="footer-left-content">
        <h2 class="white-text mb-50">Contacts</h2>
        <div class="contacts-block">
          <h5>Phone</h5>
          <a class="link-footer" href="tel:(808)555-0120">(808)555-0120</a> <br>
          <a class="link-footer" href="tel:(808)555-0116">(808)555-0116</a>
        </div>
        <div class="contacts-block">
          <h2>Office</h2>
          <p>123 Apple Str. Apple, Orchard 39495</p>
        </div>
        <div class="contacts-block">
          <h2>MAIL</h2>
          <a class="link-footer" href="mailto:example@info.com">example@info.com</a>
        </div>
      </div>

      <div class="footer-right-content">
        <h2 class="white-text mb">Let's Get In Touch</h2>
        <div class="form-footer">
          <form>
            <fieldset>
              <TwoColumnsFooter/>
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
    /* width: 100%; */
    padding-top: 50px;
    position: relative;
  }

  .footer-content {
    display: flex;
    /* width: 100%; */
  }

  .footer-left-content {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
    /* width: 50%; */
    padding-top: 50px;
  }

  .white-text.mb-50 {
    margin-bottom: 50px;
  }

  .contacts-block {
    display: flex;
    flex-direction: column;
    align-items: start;
    max-width: 317px;
    margin-bottom: 40px;
  }

  .footer-right-content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* width: 60%; */
    padding-top: 50px;
  }

  .form-footer {
    padding-top: 50px;
    display: flex;
    /* justify-content: center; */
    min-height: 50vh;
  }

  form {
    width: 50%;
  }
</style>
