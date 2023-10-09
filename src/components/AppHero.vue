
<script>
  
  import AppTitleVue from './AppTitle.vue'

  export default {
    name: 'AppHero',

    components: {
      AppTitleVue
    }
  }

</script>


<template>

  <header>
    <AppTitleVue />
  </header>

</template> 


<style>

  header {
    background-image: url('../assets/jumbo.png');
    height: 600px;
  }

</style>