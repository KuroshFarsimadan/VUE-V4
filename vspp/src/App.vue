<template>
  <div>
    <Header/>
    <div class="app-content">
      <router-view></router-view>
      <!-- <Home/> -->
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Home from "./components/Home.vue";

export default {
  name: "app",
  components: {
    Footer,
    Header,
    Home
  }
};
</script>

<style>
</style>
