<template>
    <section>
        <div class="images">
            <img src="../../assets/img/gallery_01.jpg" alt="Child">
            <img src="../../assets/img/gallery_02.jpg" alt="Child">
            <img src="../../assets/img/gallery_03.jpg" alt="Child">
            <img src="../../assets/img/gallery_04.jpg" alt="Child">
        </div>
        <div class="container-80">
            <div>See Our Kindergarten Photo Gallery!</div>
            <button>VIEW GALLERY<i class="fas fa-chevron-right"></i></button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Gallery'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    background-image: url('../../assets/img/pattern.png');
    background-size: cover;
    .images {
        display: flex;
        width: 25%;
        img {
            width: 100%;
        }
    }
    .container-80 {
        display: flex;
        justify-content: space-between;
        font-size: 30px;
        color: $white;
        padding: 30px 0;
        div {
            display: flex;
            align-items: center;
            font-weight: 300;
        }
        button {
            border: 2px solid $white;
            background-color: $mainColor;
            color: $white;
            font-weight: bold;
            padding: 15px 20px;
            i {
                margin-left: 10px;
            }
        }
    }
}

</style>