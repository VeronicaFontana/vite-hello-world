<script>
export default {
  name: "AppHero",
  data(){
    return{
      titolo: "Jumbotron"
    }
  }
}
</script>

<template>
  <h2>{{ titolo }}</h2>
</template>

<style scoped>
h2{
  background-color: red;
  color: white;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>