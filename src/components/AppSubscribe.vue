<script>
export default {
    name: 'AppSubscribe'
}
</script>

<template>
    <section id="subscription" class="p-5">
        <div class="container p-5">
            <div width="60%" class="p-5 text-center">
                <h3>Subscribe & Receive A Free eBook</h3>
                <p>Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse maximus lacus non nunc lacinia
                    lobortis.</p>
                <div>
                    <input type="text" name="" id="">
                    <button type="submit">SUBSCRIBE</button>
                </div>
                <p class="m-0">Cras porttitor pellentesque sem eu pretium.</p>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#subscription {
    background-image: url(../assets/img/subscribe-sec-bg.png);
    background-size: 130%;
    object-fit: cover;
    background-color: white;
    background-position: center;
    height: 560px;
}
</style>