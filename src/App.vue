<script>
import AppTitle from './components/AppTitle.vue';

export default {
  name: "App.vue",
  components:{
        AppTitle
      },

  data(){
    return{
      titolo: "App con Vue"
    }
  }
}
</script>

<template>
  <AppTitle />
  <h1>{{ titolo }}</h1>
  
</template>

<style>

</style>
