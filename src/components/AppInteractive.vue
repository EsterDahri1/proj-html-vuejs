<script>
import AppSocial from './AppSocial.vue';
export default {
    name: 'AppInteractive',

    components: {
        AppSocial,
    }
}
</script>

<template>
    <div class="latestRecipes d-flex justify-content-center align-items-center">
        <a href="./AppPopRecipes.vue">
            <h4>View our latest recipes</h4>
        </a>
    </div>
    <div class="cities pt-5 d-flex flex-column align-items-center justify-content-start">
        <img class="p-0 mb-0" src="../assets/img/singapore-featured-image-400x263.jpg" alt="">
        <h2 class="text-capitalise text-white text-start">City Guide: Singapore</h2>
        <a width="400" href="##" class="py-3 text-uppercase text-white text-decoration-none text-center">
            <svg class="pe-3" fill="white" xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                    d="M266.3 48.3L232.5 73.6c-5.4 4-8.5 10.4-8.5 17.1v9.1c0 6.8 5.5 12.3 12.3 12.3c2.4 0 4.8-.7 6.8-2.1l41.8-27.9c2-1.3 4.4-2.1 6.8-2.1h1c6.2 0 11.3 5.1 11.3 11.3c0 3-1.2 5.9-3.3 8l-19.9 19.9c-5.8 5.8-12.9 10.2-20.7 12.8l-26.5 8.8c-5.8 1.9-9.6 7.3-9.6 13.4c0 3.7-1.5 7.3-4.1 10l-17.9 17.9c-6.4 6.4-9.9 15-9.9 24v4.3c0 16.4 13.6 29.7 29.9 29.7c11 0 21.2-6.2 26.1-16l4-8.1c2.4-4.8 7.4-7.9 12.8-7.9c4.5 0 8.7 2.1 11.4 5.7l16.3 21.7c2.1 2.9 5.5 4.5 9.1 4.5c8.4 0 13.9-8.9 10.1-16.4l-1.1-2.3c-3.5-7 0-15.5 7.5-18l21.2-7.1c7.6-2.5 12.7-9.6 12.7-17.6c0-10.3 8.3-18.6 18.6-18.6H400c8.8 0 16 7.2 16 16s-7.2 16-16 16H379.3c-7.2 0-14.2 2.9-19.3 8l-4.7 4.7c-2.1 2.1-3.3 5-3.3 8c0 6.2 5.1 11.3 11.3 11.3h11.3c6 0 11.8 2.4 16 6.6l6.5 6.5c1.8 1.8 2.8 4.3 2.8 6.8s-1 5-2.8 6.8l-7.5 7.5C386 262 384 266.9 384 272s2 10 5.7 13.7L408 304c10.2 10.2 24.1 16 38.6 16H454c6.5-20.2 10-41.7 10-64c0-111.4-87.6-202.4-197.7-207.7zm172 307.9c-3.7-2.6-8.2-4.1-13-4.1c-6 0-11.8-2.4-16-6.6L396 332c-7.7-7.7-18-12-28.9-12c-9.7 0-19.2-3.5-26.6-9.8L314 287.4c-11.6-9.9-26.4-15.4-41.7-15.4H251.4c-12.6 0-25 3.7-35.5 10.7L188.5 301c-17.8 11.9-28.5 31.9-28.5 53.3v3.2c0 17 6.7 33.3 18.7 45.3l16 16c8.5 8.5 20 13.3 32 13.3H248c13.3 0 24 10.7 24 24c0 2.5 .4 5 1.1 7.3c71.3-5.8 132.5-47.6 165.2-107.2zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256zM187.3 100.7c-6.2-6.2-16.4-6.2-22.6 0l-32 32c-6.2 6.2-6.2 16.4 0 22.6s16.4 6.2 22.6 0l32-32c6.2-6.2 6.2-16.4 0-22.6z" />
            </svg>
            View all city guides
        </a>
    </div>
    <div class="input-group my-5">
        <div class="input-group-prepend">
            <span class="input-group-text text-center pt-3" id="basic-addon1">
                <svg fill="#ababab" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                        d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z" />
                </svg>
            </span>
        </div>
        <input type="search" class="form-control" placeholder="Search..." aria-label="Search"
            aria-describedby="basic-addon1">
    </div>
    <div class="social d-flex align-items-center">
        <a href="#" class="rounded-2 mx-1 text-center fs-5">
            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 320 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                    d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z" />
            </svg>
        </a>
        <a href="#" class="rounded-2 mx-1 text-center fs-5">
            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                    d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" />
            </svg>
        </a>
        <a href="#" class="rounded-2 mx-1 text-center fs-5">
            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                    d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z" />
            </svg>
        </a>
        <a href="#" class="rounded-2 mx-1 text-center fs-5">
            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                <path
                    d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z" />
            </svg>
        </a>
    </div>
    <div class="d-flex align-items-center mt-3 justify-content-evenly">
        <h5 class="text-capitalise p-2">Popular</h5>
        <div class="vr"></div>
        <h5 class="text-capitalise p-2">Recent</h5>
    </div>
    <ul class=" mt-3 list-unstyled">
        <li class="d-flex align-items-center justify-content-center">
            <img src="../assets/img/single-post-img3-66x66.jpg" alt="">
            <div class="ps-3">
                <a class="text-decoration-none text-black" href="##">
                    <h5>
                        Food Corner: Top Japanese Restaurants for Sushi
                    </h5>
                </a>
                <span>March 25th, 2019</span>
            </div>
        </li>
        <li class="d-flex align-items-center justify-content-center">
            <img src="../assets/img/single-post-img3-66x66.jpg" alt="">
            <div class="ps-3">
                <a class="text-decoration-none text-black" href="##">
                    <h5>
                        Food Corner: Top Japanese Restaurants for Sushi
                    </h5>
                </a>
                <span>March 25th, 2019</span>
            </div>
        </li>
        <li class="d-flex align-items-center justify-content-center">
            <img src="../assets/img/single-post-img3-66x66.jpg" alt="">
            <div class="ps-3">
                <a class="text-decoration-none text-black" href="##">
                    <h5>
                        Food Corner: Top Japanese Restaurants for Sushi
                    </h5>
                </a>
                <span>March 25th, 2019</span>
            </div>
        </li>
    </ul>
    <img class="mt-3" src="../assets/img/twitter.png" alt="">
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.latestRecipes {
    background-image: url(../assets/img/ad-bg.jpg);
    height: 433px;
    width: 400px;
    background-size: cover;
    background-position: 50% 50%;

    a {
        text-decoration: none;
        color: $food-dark;
        text-transform: uppercase;
        word-spacing: 2px;
        text-align: center;
        font-size: 17px;
        letter-spacing: 0.5px;
        line-height: 50px;
        width: 40%;
    }
}


.cities {
    position: relative;

    a {
        background-color: $food-warning;
        width: 400px;
    }

    h2 {
        position: absolute;
        top: 52%;
        right: 23%;
        display: inline;
        font-size: 25px;
        font-weight: 600;
        letter-spacing: 1px;
        line-height: 37.5px;
        text-align: left;
        background-color: rgba(0, 0, 0, 0.8);
        padding: 10px 22px;
        padding-left: 0;
    }
}

input {
    background-color: #ffffff;
    border-color: #dfdfdd;
    border-radius: 6px;
    border-style: solid;
    border-width: 1.6px;
    color: #ababab;
    display: inline-block;
    width: 400px;
    height: 56px;
    border-left: none;
}

.input-group-text {
    background-color: #ffffff;
    border-color: #dfdfdd;
    border-radius: 6px;
    border-style: solid;
    border-width: 1.6px;
    color: #ababab;
    display: inline-block;
    height: 56px;
    border-right: none;
}

.social {
    a {
        background-color: white;
        width: 36px;
        aspect-ratio: 1 / 1;
        text-align: center;

        svg {
            fill: $food-grey;
        }
    }
}

.vr {
    border-left: 1px dashed $food_grey;
    border-radius: 30px;
    padding: 3px;
    background-color: transparent;
}

li {
    img {
        border-radius: 50%;
    }
}
</style>