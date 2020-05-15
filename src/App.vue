<template>
  <div id="app">
    <div class="site-wrapper clearfix">
      <div class="site-overlay"></div>
      <NavBar></NavBar>
      <div class="site-content">
        <div class="container">
          <router-view />
        </div>
      </div>
      <Footer></Footer>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
import NavBar from "./components/NavBar.vue";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    NavBar,
    Footer
  },
};
</script>

<style>

</style>
