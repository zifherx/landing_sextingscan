<template>
    <v-container>
        <Sexting/>
        <!-- <Carrusel class="mt-5"/> -->
        <!-- <Landing class="mt-5"/> -->
        <h1 class="pink--text text-uppercase text-center mt-10">Etapas</h1>
        <Listas class="mt-5"/>
        <h1 class="pink--text text-uppercase text-center mt-10">Equipo</h1>
        <Team class="mt-5"/>
    </v-container>
</template>
<script>
import Landing from '../components/Landing.vue'
import Carrusel from '../components/Carrusel.vue'
import Sexting from '../components/Sexting.vue'
import Listas from '../components/Listas.vue'
import Team from '../components/Team.vue'

export default {
    name: 'Inicio',
    components: {
        Carrusel,
        Landing,
        Sexting,
        Listas,
        Team
    }
}
</script>