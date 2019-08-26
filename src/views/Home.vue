<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.jpg" />
    <MainComponent msg="Welcome to our first Vue.js App" />
  </div>
</template>

<script>
import MainComponent from "@/components/MainComponent.vue";

export default {
  name: "home",
  components: {
    MainComponent
  }
};
</script>
