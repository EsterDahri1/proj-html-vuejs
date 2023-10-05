<script>
export default {
    name: 'AppJournal'
}
</script>

<template>
    <section id="journal">
        <div class="container">
            <div class="window">
                <h6 class="text-uppercase">FOODIE JOURNAL</h6>
                <div class="row">
                    <div class="col-4">
                        <div class="card">
                            <div class="img-card-top">
                                <img src="../assets/img/" alt="">
                            </div>
                            <div class="card-body">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card">
                            <div class="img-card-top"></div>
                            <div class="card-body">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card">
                            <div class="img-card-top"></div>
                            <div class="card-body">
                                <h5><a href="#">Food Corner: Top Japanese Restaurants for Sushi</a></h5>
                                <span>By <a href="#">admin</a> | March 25th, 2019</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
#journal {
    height: 386px;

    .window {
        background-color: white;
        height: 450px;
    }
}
</style>