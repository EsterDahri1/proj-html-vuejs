<script>
export default {
    name: 'AppSubscribe'
}
</script>

<template>
    <section id="subscription">
        <div class="container">
            <div>
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
    background-size: cover;
    background-color: white;
}
</style>