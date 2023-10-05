<script>
export default {
    name: 'AppArticles',
}
</script>

<template>
    <div class="card border-0 rounded-0">
        <img src="../assets/img/Yogurt-Nan-600x395.jpg" class="card-img-top rounded-0" alt="...">
        <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                of the card's content.
            </p>
        </div>
    </div>
    <div id="recipesMenu" class="row g-4 pb-3 align-items-center justify-content-center">
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <div class="col-6 ">
            <div class="card border-0 rounded-0">
                <img width="100%" src="../assets/img/Mixed-fruits.jpg" class="card-img-top rounded-0" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <h6 class="card-subtitle mb-2 text-muted ">Card subtitle</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.
                    </p>
                </div>
            </div>
        </div>
        <a class="py-3 mt-4 text-center text-decoration-none" href="#">LOAD MORE</a>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#recipesMenu {
    margin-top: 20px;
}

a {
    background-color: #67615a1a;
    color: $food-grey;
    word-spacing: 1px;
    width: 97%;
}
</style>