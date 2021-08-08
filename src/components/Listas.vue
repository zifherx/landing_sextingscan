<template>
  <v-container>
    <v-row class="fill-height" align="center" justify="center">
      <v-col cols="12" sm="12" md="4" lg="4">
        <v-hover v-slot="{hover}">
          <v-card :elevation="hover ? 12 : 2" :class="{'on-hover': hover}" height="200">
            <v-card-text>
              <h1 class="pink--text text-uppercase text-center mt-15">Identifica</h1>
            </v-card-text>
            <v-expand-transition>
              <div v-if="hover" class="d-flex white darken-2 v-card--reveal text-h2 black--text">
                <v-card :class="{'on-hover': hover}" height="200">
                  <v-card-title class="pink--text text-uppercase">Identifica</v-card-title>
                  <v-card-text>
                    <p class="text-justify"
                      >Reconocer la violencia es el primer paso para cuidarnos. Ten presente que el sexting se convierte en un
                      <strong>delito</strong> cuando este es <strong>No concensuado</strong>.</p
                    >
                  </v-card-text>
                </v-card>
              </div>
            </v-expand-transition>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="12" md="4" lg="4">
        <v-hover v-slot="{hover}">
          <v-card :elevation="hover ? 12 : 2" :class="{'on-hover': hover}" height="200">
            <v-card-text>
              <h1 class="pink--text text-uppercase text-center mt-15">Resiste</h1>
            </v-card-text>
            <v-expand-transition>
              <div v-if="hover" class="d-flex white darken-2 v-card--reveal text-h2 black--text">
                <v-card :class="{'on-hover': hover}" height="200">
                  <v-card-title class="pink--text text-uppercase">Resiste</v-card-title>
                  <v-card-text>
                    <p class="text-justify">
                      Crea un plan de <strong>seguridad digital</strong>, mejora tu seguridad y privacidad en redes sociales y practica el
                      <strong>sexting seguro</strong> para mejorar tu privacidad en línea.</p
                    >
                  </v-card-text>
                </v-card>
              </div>
            </v-expand-transition>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="12" md="4" lg="4">
        <v-hover v-slot="{hover}">
          <v-card :elevation="hover ? 12 : 2" :class="{'on-hover': hover}" height="200">
            <v-card-text>
              <h1 class="pink--text text-uppercase text-center mt-15">Denuncia</h1>
            </v-card-text>
            <v-expand-transition>
              <div v-if="hover" class="d-flex white darken-2 v-card--reveal text-h2 black--text">
                <v-card :class="{'on-hover': hover}" height="200">
                  <v-card-title class="pink--text text-uppercase">Denuncia</v-card-title>
                  <v-card-text>
                    <p class="text-justify">
                      En el Perú contamos con diferentes tipos de protección ante la violencia de género en línea, en algunas situaciones incluye una
                      sanción de <strong>cárcel</strong>.
                    </p>
                  </v-card-text>
                </v-card>
              </div>
            </v-expand-transition>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
  export default {
    name: "Listas",
  };
</script>
<style scoped>
  .v-card:not(.on-hover) {
    opacity: 0.7;
  }

  .v-card--reveal {
    align-items: center;
    bottom: 0;
    justify-content: center;
    position: absolute;
    width: 100%;
    /* height: auto; */
    transition: opacity 0.4s ease-in-out;
  }
</style>
