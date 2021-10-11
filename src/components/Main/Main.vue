<template>
    <main>
        <Hero/>
        <LearnMore/>
        <WelcomeToFable/>
        <Overview/>
    </main>
  
</template>

<script>
import Hero from './Hero.vue';
import LearnMore from './LearnMore.vue';
import WelcomeToFable from './WelcomeToFable.vue';
import Overview from './Overview.vue';

export default {
    name: 'Main',
    components: {
        Hero,
        LearnMore,
        WelcomeToFable,
        Overview
    }
}
</script>

<style lang="scss">

</style>