<template>
    <main>
        <Hero/>
        <LearnMore/>
    </main>
  
</template>

<script>
import Hero from './Hero.vue';
import LearnMore from './LearnMore.vue';

export default {
    name: 'Main',
    components: {
        Hero,
        LearnMore
    }
}
</script>

<style lang="scss">

</style>