<script>
export default {
    name: 'AppJournal'
}
</script>

<template>
    <section id="journal">
        <div class="container">
            <div class="window">
                <h6 class="text-uppercase text-center pb-4">FOODIE JOURNAL</h6>
                <div class="row">
                    <div class="col-4">
                        <article class="card border-0 d-flex flex-column align-items-center justify-content-center">
                            <div class="img-card-top">
                                <img src="../assets/img/single-post-img3.jpg" alt="">
                            </div>
                            <div class="card-body d-flex flex-column align-items-center justify-content-center text-center">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </article>
                    </div>
                    <div class="col-4">
                        <article class="card border-0 d-flex flex-column align-items-center justify-content-center">
                            <div class="img-card-top">
                                <img src="../assets/img/fi-roundup.jpg" alt="">
                            </div>
                            <div class="card-body d-flex flex-column align-items-center justify-content-center text-center">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </article>
                    </div>
                    <div class="col-4">
                        <article class="card border-0 d-flex flex-column align-items-center justify-content-center">
                            <div class="img-card-top">
                                <img src="../assets/img/fi-toasts.jpg" alt="">
                            </div>
                            <div class="card-body d-flex flex-column align-items-center justify-content-center text-center">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </article>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#journal {
    height: 386px;
    position: relative;

    .container {
        position: absolute;
        top: -21%;
        left: 10%;

        .window {
            background-color: white;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            max-width: 1200px;
            padding: 30px 25px;

            img {
                height: 228px;
            }

            h5 {
                font-family: 'Vidaloka';
                width: 75%;
            }

            a {
                text-decoration: none;
                color: $food-dark;
            }

            a:hover {
                color: $food-warning;
            }

            span {
                font-size: 15px;
                color: $food-grey;
            }
        }
    }
}
</style>