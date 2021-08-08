<template>
  <div>
    <v-row>
      <v-col cols="12" sm="12" md="6" lg="6">
          <v-row class="align-center justify-center">
            <v-col cols="12" sm="12" md="8" lg="8">
              <v-card class="mt-15">
                <v-card-title class="pink--text text-uppercase text-center justify-center">¿Qué es Sexting?</v-card-title>
                <v-card-text>
                  <p class="text-justify">
                    Se denomina sexting a la actividad de enviar fotos, videos o mensajes de contenido sexual o erótico a través de dispositivos
                    tecnológicos, ya sea utilizando aplicaciones de mensajería instantánea, redes sociales, correo electrónico u otra herramienta de
                    comunicación.
                  </p>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
      </v-col>
      <v-col cols="12" sm="12" md="6" lg="6">
        <v-img :src="require('../assets/6490.jpg')" contain></v-img>
      </v-col>
    </v-row>
  </div>
</template>
<script>
  export default {
    name: "Sexting",
  };
</script>
<style>
  .hola {
    border: 1px solid black;
    height: 500px;
  }
</style>
