<template>
    <main>
        <Hero/>
        <LearnMore/>
        <WelcomeToFable/>
    </main>
  
</template>

<script>
import Hero from './Hero.vue';
import LearnMore from './LearnMore.vue';
import WelcomeToFable from './WelcomeToFable.vue';

export default {
    name: 'Main',
    components: {
        Hero,
        LearnMore,
        WelcomeToFable
    }
}
</script>

<style lang="scss">

</style>