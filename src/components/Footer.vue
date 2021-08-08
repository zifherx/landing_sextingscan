<template>
  <v-footer :color="colorFooter" dark padless>
    <v-container>
      <v-card flat tile width="100%" color="transparent" class="text-center">
        <v-card-text>
          <v-btn icon class="mx-4" to="/">
            <v-icon size="24px">mdi-home</v-icon>
          </v-btn>
          <v-btn icon class="mx-4">
            <v-icon size="24px">mdi-email</v-icon>
          </v-btn>
        </v-card-text>
        <v-divider class="mx-4"></v-divider>
        <v-card-text class="white--text">
          <p class="mb-0">Taller Proyecto Integrador - UPAO <strong><v-icon small>mdi-school</v-icon></strong></p>
          <p class="mb-0">{{ new Date().getFullYear() }} — <strong>SextingScan &copy;</strong> </p>
        </v-card-text>
      </v-card>
    </v-container>
  </v-footer>
</template>
<script>
  export default {
    name: "Footer",
    data() {
      return {
        colorFooter: "#E91E63",
      };
    },
  };
</script>
