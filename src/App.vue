<script>
export default {
  name: 'App'
}
</script>

<template>
  <body>
    <header>
      <div class="container p-4 d-flex flex-column justify-content-center">
        <div class="d-flex justify-content-between align-items-start">
          <div id="interactWithUs">
            <ul id="download" class="list-unstyled d-flex">
              <li class="m-1 ps-2 pe-2">
                <span class="text-capitalize">
                  <a href="#" class="text-black text-decoration-none">download app</a>
                </span>
              </li>
              <li class="m-1 ps-2 pe-2">
                <span class="">
                  <a href="#" class="text-black text-decoration-none">Advertise with us</a>
                </span>
              </li>
            </ul>
          </div>
          <div id="logo" class="text-center">
            <img class="m-1" height="120px" src="./assets/img/avada-food-logo-2x.png" alt="">
          </div>
          <div id="social" class="d-flex justify-content-end">
            <a href="#" class="ps-2 pe-2 fs-5">
              <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 320 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                  d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z" />
              </svg>
            </a>
            <a href="#" class="ps-2 pe-2 fs-5">
              <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                  d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" />
              </svg>
            </a>
            <a href="#" class="ps-2 pe-2 fs-5">
              <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                  d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z" />
              </svg>
            </a>
            <a href="#" class="ps-2 pe-2 fs-5">
              <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                  d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z" />
              </svg>
            </a>
          </div>
        </div>
        <div>
          <nav>
            <ul class="list-unstyled d-flex align-items-center justify-content-center">
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    Home
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    Recipes
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    Places
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    Blog
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    about
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    contact
                  </span>
                </a>
              </li>
              <li>
                <a class="text-capitalize text-decoration-none text-center text-black fs-6" href="#">
                  <span>
                    <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                      viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                      <path
                        d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z" />
                    </svg>
                  </span>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </header>
    <main></main>
    <footer></footer>
  </body>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
  background-color: $food_light;
  font-family: 'Catamaran', sans-serif;

  header {
    height: 230px;

    #download {
      font-size: 14px;
    }

    #interactWithUs,
    #social {
      width: 30%;
    }

    #logo {
      width: 40%;
    }

    nav {
      ul {
        padding: 20px
      }

      a {
        padding: 20px 10px;
        font-weight: 600;
        margin: 0.5rem;
      }

      a.active {
        border-bottom: 2px solid $food_warning;
        color: $food_warning;
      }
    }
  }
}
</style>
