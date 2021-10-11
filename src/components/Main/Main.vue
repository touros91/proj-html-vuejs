<template>
    <main>
        <Hero/>
        <LearnMore/>
        <WelcomeToFable/>
        <Overview/>
        <Classes/>
    </main>
  
</template>

<script>
import Hero from './Hero.vue';
import LearnMore from './LearnMore.vue';
import WelcomeToFable from './WelcomeToFable.vue';
import Overview from './Overview.vue';
import Classes from './Classes.vue';

export default {
    name: 'Main',
    components: {
        Hero,
        LearnMore,
        WelcomeToFable,
        Overview,
        Classes
    }
}
</script>

<style lang="scss">

</style>