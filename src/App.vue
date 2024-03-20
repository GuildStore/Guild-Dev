<template>
  <div id="app">
    <div class="top">
      <!-- <Navbar /> -->
    </div>
    <div class="content">
      <router-view />
    </div>
    <div class="bottom"></div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style>
@import "./style/main.css";
</style>
