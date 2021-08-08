<template>
  <v-container>
    <v-row align="center" justify="center">
      <v-col v-for="(card, i) in cards" :key="i" cols="12" sm="12" md="4" lg="4">
        <v-card>
          <v-img :src="card.img" height="300px"></v-img>
          <v-card-title>
            {{ card.title }} - 
            <v-chip :color="colorChip" dark class="mx-2">{{ card.cargo }}</v-chip>
          </v-card-title>
          <v-divider></v-divider>
          <v-card-actions class="white justify-center">
            <v-btn v-for="(social, i) in socials" :key="i" small fab icon class="white--text" :color="social.color">
              <v-icon>{{ social.icon }}</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
  export default {
    name: "Team",
    data() {
      return {
        colorChip: "#E91E63",
        cards: [
          {title: "Walter Cueva", img: require("../assets/img_cueva.jpg"), cargo: "Manager"},
          {title: "Ali Lozano", img: require("../assets/img_ali.jpg"), cargo: "Product Owner"},
          {title: "Elias Santacruz", img: require("../assets/img_elias.jpg"), cargo: "Product Owner"},
          {title: "Sergio Lavalle", img: require("../assets/img_lavalle.jpg"), cargo: "Scrum Master"},
          {title: "Fernando Rojas", img: require("../assets/gg.png"), cargo: "Project Manager"},
        ],
        socials: [
          {
            icon: "mdi-facebook",
            color: "indigo",
          },
          {
            icon: "mdi-linkedin",
            color: "cyan darken-1",
          },
          {
            icon: "mdi-instagram",
            color: "red lighten-3",
          },
        ],
      };
    },
  };
</script>
