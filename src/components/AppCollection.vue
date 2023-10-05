<script>
export default {
    name: 'AppCollection'
}
</script>

<template>
    <section id="collection">
        <div class="container">
            <div class="titleDesc d-flex flex-column align-items-center justify-content-center text-center pt-5 pb-5">
                <h2 class="text-uppercase">CULINARY COLLECTION</h2>
                <p class="p-3">Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse maximus lacus
                    non nunc lacinia lobortis.
                </p>
            </div>
            <div class="collection">
                <div class="row">
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
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

.card-body {
    a {
        color: $food-dark;
    }

    a:hover {
        background-color: $food-warning;
        color: white;

    }
}
</style>