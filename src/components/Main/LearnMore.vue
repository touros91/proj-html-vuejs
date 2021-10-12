<template>
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
    padding: 50px 0;
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
            border: 2px solid $white;
            background-color: $mainColor;
            color: $white;
            font-weight: bold;
            padding: 15px 20px;
            i {
                margin-left: 5px;
            }
        }
    }
}
</style>