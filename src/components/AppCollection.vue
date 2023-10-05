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
</style>