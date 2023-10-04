<script>
export default {
    name: 'AppFooter',
}
</script>

<template>
    <footer>
        <div class="links">
            <div class="container">
                <div class="row g-2 text-nowrap justify-content-evenly align-items-start">
                    <div class="col-2">
                        <div>
                            <img src="../assets/img/avada-food-logo-mob-2x-200x87.png" alt="" class="">
                            <div class="card-body">
                                <!--<AppSocial/>-->
                                ciao
                            </div>
                        </div>
                    </div>
                    <div class="vr"></div>
                    <div class="col-2">
                        <nav>
                            <ul class="list-unstyled d-flex flex-column align-items-start justify-content-start">
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
                            </ul>
                        </nav>
                    </div>
                    <div class="vr"></div>
                    <div class="col-2">
                        <h6 class="text-uppercase">contact us</h6>
                    </div>
                    <div class="vr"></div>
                    <div class="col-2">
                        <h6 class="text-uppercase">get our app</h6>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright text-center pt-4">
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
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;

footer {
    height: 350px;

    img {
        width: 192px;
    }

    .links {
        background-color: white;
        padding: 52px 25px;

        li {
            margin-bottom: 1rem;
        }
    }

    .copyright {
        color: $food_grey;
        font-size: 13px;
        padding: 8px 25px;

        a {
            color: $food_dark;
        }

        a:hover {
            color: $food_warning;
        }
    }

    .vr {
        border-left: 1px dashed $food_grey;
        border-radius: 30px;
        padding: 3px;
        background-color: transparent;
    }

    h6 {
        color: $food_warning;
    }
}
</style>