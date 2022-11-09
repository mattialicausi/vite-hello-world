<template>

  <AppHero/>

 <MainComponent />

</template>

<script>
  import AppHero from './components/AppHero.vue';
  import MainComponent from './components/MainComponent.vue';

  export default {
    components: {
    MainComponent,
    AppHero,
},
    data() {
      return {
        //return
      }
    }
    
  }
</script>

<style lang="css">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

</style>
