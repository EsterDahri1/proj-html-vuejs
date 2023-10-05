<script>
import AppJumbo from './AppJumbo.vue';
import AppJournal from './AppJournal.vue';
import AppPopRecipes from './AppPopRecipes.vue';
import AppCollection from './AppCollection.vue';
import AppSubscribe from './AppSubscribe.vue';
import AppBanner from './AppBanner.vue';
export default {
    name: 'AppMain',
    components: {
        AppJumbo,
        AppJournal,
        AppPopRecipes,
        AppCollection,
        AppSubscribe,
        AppBanner
    }
}
</script>

<template>
    <AppJumbo />
    <AppJournal />
    <AppPopRecipes />
    <AppCollection />
    <section id="blog">

    </section>
    <AppSubscribe />
    <AppBanner />
</template>

<style lang="scss">
@use '../assets/scss/partials/variables' as *;
</style>