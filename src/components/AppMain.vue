<script>
import AppJumbo from './AppJumbo.vue';
import AppSubscribe from './AppSubscribe.vue';
import AppBanner from './AppBanner.vue';
export default {
    name: 'AppMain',
    components: {
        AppJumbo,
        AppSubscribe,
        AppBanner
    }
}
</script>

<template>
    <AppJumbo />
    <section id="journal">

    </section>
    <section id="popRecipes">

    </section>
    <section id="collection">

    </section>
    <section id="blog">

    </section>
    <AppSubscribe />
    <AppBanner />
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;
</style>