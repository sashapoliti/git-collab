<template>
  <HeaderComponent />
  <MainComponent />
  <FooterComponent />
</template>

<script>
import MainComponent from './components/MainComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
  export default {
    name: 'App',
    components: {
      MainComponent,
      HeaderComponent,
      FooterComponent
    }
  }
</script>

<style lang="scss" scoped>

</style>