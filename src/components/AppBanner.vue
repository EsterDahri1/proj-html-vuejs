<script>
export default {
    name: 'AppBanner',
}
</script>

<template>
    <div id="banner">
        <div class="row g-0">
            <div class="col-3">
                <img src="../assets/img/Yogurt-Nan-400x263.jpg" alt="">
            </div>
            <div class="col-3">
                <img src="../assets/img/Mixed-fruits-400x263.jpg" alt="">
            </div>
            <div class="col-3">
                <img src="../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="">
            </div>
            <div class="col-3">
                <img src="../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

img {
    height: 250px;
}
</style>