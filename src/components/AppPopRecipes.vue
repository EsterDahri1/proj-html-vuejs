<script>
export default {
    name: 'AppPopRecipes.vue'
}
</script>

<template>
    <section id="popRecipes">
        <div class="container">
            <div class="recipes pt-5 pb-5">
                <div class="titleDesc d-flex flex-column align-items-center justify-content-center text-center pt-5 pb-5">
                    <h2>POPULAR RECIPES</h2>
                    <p class="p-3">Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse maximus lacus
                        non nunc lacinia lobortis.
                    </p>
                </div>
                <div class="row">
                    <div class="col-6 pe-4">
                        <div class="card">
                            <img src="../assets/img/Yogurt-Nan-600x395.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                    of the card's content.</p>
                                b5
                            </div>
                        </div>
                    </div>
                    <div class="right col-6 ps-4">
                        <div id="recipesMenu" class="row g-4">
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                            <div class="col-6 ">
                                <img width="100%" src="../assets/img/Mixed-fruits.jpg" alt="">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scope>
@use '../assets/scss/partials/variables' as *;

.titleDesc {
    width: 50%;
    margin: auto;

    h2 {
        font-size: 16px;
        color: $food-dark;
        letter-spacing: 2px;
    }

    p {
        font-size: 17px;
        color: $food-grey;
    }
}
</style>