<!-- JAVASCRIPT -->
<script>

  export default {

    name: 'AppTitle',

    data() {
      return {
        titolo: 'La mia prima app con Vite!'
      }
    },

  }

</script>


<!-- HTML -->
<template>

  <h1>{{ titolo }}</h1>

</template>


<!-- CSS -->
<style scoped>

  h1 {
    padding-top: 50px;
    font-size: 50px;
    text-align: center;
    color: white;
  }

</style>