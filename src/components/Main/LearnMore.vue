<template>
    <!-- Learn More section  -->
    <section>
        <div class="container-80">
            <div>How to Enroll Your Child to a Class?</div>
            <button>LEARN MORE <i class="fas fa-chevron-right"></i></button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'LearnMore'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    background-color: $mainColor;
    padding: 30px 0;
    .container-80 {
        display: flex;
        justify-content: space-between;
        font-size: 30px;
        color: $white;
        div {
            display: flex;
            align-items: center;
            font-weight: 300;
        }
        button {
            @include violetButton;
            i {
                margin-left: 10px;
            }
        }
        button:hover {
            background-color: $white;
            color: $mainColor;
        }
    }
}
</style>