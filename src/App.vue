<template>
  <SiteHeader/>
  <DespreNoi/>
  <IntrebariFrecvente/>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';
import DespreNoi from './components/DespreNoi.vue';
import IntrebariFrecvente from './components/IntrebariFrecvente.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    DespreNoi,
    IntrebariFrecvente
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
