<script>
// importazione componenti
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
// esportazione
export default {
  data() {
    return {

    };
  },
  components: {
    AppTitle,
    AppHero,
  },
}
</script>

<template>

  <AppTitle></AppTitle>
  <AppHero></AppHero>

</template>

<style scoped>
  .container {
    display: flex;
    position: relative;
    justify-content: center;
    align-items: center;
  }
  
</style>