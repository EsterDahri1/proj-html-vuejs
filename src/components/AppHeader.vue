<script>
import AppSocial from './AppSocial.vue';
import AppLogo from './AppLogo.vue';
export default {
    name: 'AppHeader',
    components: {
        AppLogo,
        AppSocial
    }
}
</script>

<template>
    <header>
        <div class="container p-4 d-flex flex-column justify-content-center">
            <div class="d-flex justify-content-between align-items-start">
                <div id="interactWithUs">
                    <ul id="download" class="list-unstyled d-flex">
                        <li class="m-1 ps-2 pe-2">
                            <span class="text-capitalize">
                                <a href="#" class="text-decoration-none">download app</a>
                            </span>
                            <span class="iOS">iOS</span>
                        </li>
                        <li class="m-1 ps-2 pe-2">
                            <span class="">
                                <a href="#" class="text-decoration-none">Advertise with us</a>
                            </span>
                        </li>
                    </ul>
                </div>
                <AppLogo />
                <AppSocial />
            </div>
            <div>
                <nav>
                    <ul class="list-unstyled d-flex align-items-center justify-content-center">
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    Home
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    Recipes
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    Places
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    Blog
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    about
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
                                <span>
                                    contact
                                </span>
                            </a>
                        </li>
                        <li>
                            <a class="text-capitalize text-decoration-none text-center fs-6" href="#">
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
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;

header {
    height: 230px;

    #download {
        font-size: 12px;
        color: $food_grey;

        a:hover {
            border-bottom: 2px solid $food_warning;
            color: $food_warning;
            transition: 0.2s;

            svg {
                fill: $food_warning;
            }
        }

        .iOS {
            border-radius: 3px;
            font-size: 9.8px;
            letter-spacing: 0.2px;
            line-height: 9.8px;
            margin: 0px 0px 0px 7.35px;
            padding: 3.43px 5.39px;
            text-align: center;
            color: white;
            background-color: $food_warning;
        }
    }

    #interactWithUs {
        width: 30%;

        a {
            color: $food_grey;

            svg {
                fill: $food_grey;
            }
        }
    }

    nav {
        ul {
            padding: 20px
        }

        a {
            padding: 20px 10px;
            font-weight: 600;
            margin: 0.5rem;
            color: $food_dark;
        }

        a.active,
        a:hover {
            border-bottom: 2px solid $food_warning;
            color: $food_warning;
            transition: 0.2s;

            svg {
                fill: $food_warning;
            }
        }
    }
}
</style>