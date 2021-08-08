<template>
  <v-app>
    <Navbar />
    <v-main class="fondoWeb">
      <router-view />
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>
  import Navbar from "./components/Navbar.vue";
  import Footer from './components/Footer.vue'

  export default {
    name: "App",
    components: {
      Navbar,
      Footer
    },
  };
</script>
<style>
  .fondoWeb {
    /* border: 1px solid red; */
    background-color: #e3e9ff;
  }
</style>
