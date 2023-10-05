<script>
import AppJumbo from './AppJumbo.vue';
import AppJournal from './AppJournal.vue';
import AppPopRecipes from './AppPopRecipes.vue';
import AppSubscribe from './AppSubscribe.vue';
import AppBanner from './AppBanner.vue';
export default {
    name: 'AppMain',
    components: {
        AppJumbo,
        AppJournal,
        AppPopRecipes,
        AppSubscribe,
        AppBanner
    }
}
</script>

<template>
    <AppJumbo />
    <AppJournal />
    <AppPopRecipes />
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