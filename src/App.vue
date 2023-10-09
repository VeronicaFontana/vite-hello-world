<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

export default {
  name: "App.vue",
  components:{
        AppTitle,
        AppHero
      },

  data(){
    return{
      titolo: "App con VITE"
    }
  }
}
</script>

<template>
  <AppTitle />
  <AppHero />
  <p>{{ titolo }}</p>
</template>

<style>
body{
  text-align: center;
}
</style>
