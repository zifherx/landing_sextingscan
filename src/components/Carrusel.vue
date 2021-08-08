<template>
    <v-carousel cycle show-arrows-on-hover hide-delimiter-background>
        <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src" reverse-transition="fade-transition" transition="fade-transition">
        </v-carousel-item>
    </v-carousel>
</template>
<script>
export default {
    name: 'Carrusel',
    data(){
        return{
            items: [
                { src: require('../assets/emoji-faces-social-media.jpg')},
                { src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'},
                { src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'}
            ] 
        }
    }
}
</script>