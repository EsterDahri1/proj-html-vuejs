<script>
import AppJumbo from './AppJumbo.vue';
import AppBanner from './AppBanner.vue';
export default {
    name: 'AppMain',
    components: {
        AppJumbo,
        AppBanner,
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
    <section id="subscription">

    </section>
    <AppBanner />
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;
</style>