<template>
  <div id="app">
    <div class="container">
      <pp-header></pp-header>
    </div>
    <div class="home">
      <pp-menu></pp-menu>
    </div>
    <div class="footer">
      <pp-footer></pp-footer>
    </div>
  </div>
</template>



<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Home from "./components/Home.vue";
import Menu from "./components/Menu.vue";

export default {
  components: {
    ppHeader: Header,
    ppFooter: Footer,
    ppHome: Home,
    ppMenu: Menu
  }
};
</script>



<style>
</style>
