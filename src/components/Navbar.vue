<template>
  <v-app-bar :color="colorNavbar" dark app>
    <v-btn plain to="/">
      <v-img :src="require('../assets/sexting.svg')" width="40" alt="Sexting Social" contain></v-img>
      <v-toolbar-title class="text-capitalize ml-2">SextingScan</v-toolbar-title>
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn plain href="https://sextingscan.site/social" target="_blank">Red Social</v-btn>
    <v-btn plain to="/plugin">Plugin</v-btn>
  </v-app-bar>
</template>
<script>
  export default {
    name: "Navbar",
    data() {
      return {
        colorNavbar: "#E91E63",
      };
    },
  };
</script>
