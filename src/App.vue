<script>
import AppHeader from './components/AppHeader.vue'
export default {
  name: 'App',
  components: {
    AppHeader,

  }
}
</script>

<template>
  <body>
    <AppHeader />
    <main></main>
    <footer></footer>
  </body>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
  background-color: $food_light;
  font-family: 'Catamaran', sans-serif;
}
</style>
