<template>
    <!-- Google Maps image section  -->
    <section>
        <div class="google-maps"></div>
    </section>
</template>

<script>
export default {
    name: 'GoogleMaps'
}
</script>

<style lang="scss" scoped>
section {
    height: 400px;
    .google-maps {
        width: 100%;
        height: 100%;
        background-image: url('../../assets/img/full_map.png');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: initial;
    }
}
</style>