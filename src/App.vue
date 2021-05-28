<template>
  <div id="app">
    <TitleComponent />
    <HeroComponent />
  </div>
</template>

<script>
import TitleComponent from '@/components/TitleComponent.vue';
import HeroComponent from './components/HeroComponent.vue';

export default {
  name: 'App',
  components: {
    TitleComponent,
    HeroComponent
  }
}
</script>

<style 
    HeroComponentlang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
