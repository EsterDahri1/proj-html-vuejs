<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <body>
    <AppHeader />
    <AppMain />
    <AppFooter />
  </body>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
  background-color: $food_light;
  font-family: 'Catamaran', sans-serif;
}
</style>
