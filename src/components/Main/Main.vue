<template>
    <main>
        <Hero/>
        <LearnMore/>
        <WelcomeToFable/>
        <Overview/>
        <Classes/>
        <Goals/>
        <Gallery/>
        <Reviews/>
    </main>
  
</template>

<script>
import Hero from './Hero.vue';
import LearnMore from './LearnMore.vue';
import WelcomeToFable from './WelcomeToFable.vue';
import Overview from './Overview.vue';
import Classes from './Classes.vue';
import Goals from './Goals.vue';
import Gallery from './Gallery.vue';
import Reviews from './Reviews.vue';

export default {
    name: 'Main',
    components: {
        Hero,
        LearnMore,
        WelcomeToFable,
        Overview,
        Classes,
        Goals,
        Gallery,
        Reviews
    }
}
</script>

<style lang="scss">


</style>