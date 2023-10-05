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
            <div class="collection pb-5">
                <div class="row g-5">
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
                            <div class="img-card-top">
                                <img src="../assets/img/drinks-recipes.png" alt="">
                            </div>
                            <div class="card-body">
                                <a href="#" class=" text-uppercase">drinks</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="card p-4 border-0 rounded-0">
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

.card {
    width: 100%;

    img {
        width: 96px;
        aspect-ratio: 1 / 1;
    }

    .card-body {
        a {
            color: $food-dark;
            text-decoration: none;
        }

        a:hover {
            background-color: $food-warning;
            color: white;
            padding: 1rem 4.5rem;

        }
    }
}

.card:hover {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>