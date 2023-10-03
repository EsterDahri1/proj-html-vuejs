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
    <footer>
      <div class="links">
        <div class="container">
          <div class="row row-cols-3"></div>
        </div>
      </div>
      <div class="copyright text-center">
        <p>
          &copy; Copyright 2012 - 2020 |
          <a class="text-decoration-none text-capitalize" href="#">
            Avada Website Builder
          </a> by
          <a class="text-decoration-none text-capitalize" href="#">
            ThemeFusion
          </a>
          | All Rights Reserved | Powered by WordPress
        </p>
      </div>
    </footer>
  </body>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
  background-color: $food_light;
  font-family: 'Catamaran', sans-serif;

  footer {
    height: 350px;

    .links {
      background-color: white;
    }

    .copyright {
      color: $food_grey;
      font-size: 13px;

      a {
        color: black;
      }

      a:hover {
        color: $food_warning;
      }
    }
  }
}
</style>
