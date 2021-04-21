<template>
  <div id="app">
    <div class="m-flexContainer">
      

      <div class="m-formContainer">
        <LoginForm :title="headerText" />
      </div>
    </div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
import LoginForm from "./components/LoginForm.vue";

export default {
  name: "app",
  data() {
    return {
      headerText: "Login"
    };
  },
  components: {
    LoginForm
  }
};
</script>

<style lang="scss">
/* GLOBAL SCSS IMPORT */
@import "./scss/main.scss";

</style>
