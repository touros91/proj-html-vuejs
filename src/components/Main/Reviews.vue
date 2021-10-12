<template>
    <!-- Reviews section  -->
    <section>
        <div class="container-80">
            <div class="image">
                <img src="../../assets/img/quote_alt.png" alt="Quote">
            </div>
            <p>I have to say that I have 2 children ages 5 and 2 and have used various daycare's Kindergartens and this is by far the very best I have ever used.</p>
            <hr>
            <div class="customer">Cecil J. Kirk</div>
            <div class="small-boxes-container">
                <div class="small-box"></div>
                <div class="small-box"></div>
                <div class="small-box" id="box-up"></div>
                <div class="small-box"></div>
                <div class="small-box"></div>
                <div class="small-box"></div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Reviews'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    background-image: url('../../assets/img/parallax_02.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    height: 470px;
    .container-80 {
        padding: 50px 0;
        .image {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 2px solid $white;
            padding: 21px;
            margin: auto;
            img {
                width: 100%;
            }
        }
        p {
            font-size: 37px;
            color: $white;
            font-weight: 300;
            text-align: center;
            padding: 30px 0;
        }
        hr {
            width: 50px;
            margin: auto;
            border: 1px solid $white;
        }
        .customer {
            text-align: center;
            margin: 20px 0 40px 0;
            color: $white;
            font-size: 20px;
        }
        .small-boxes-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 50px;
            .small-box {
                width: 40px;
                height: 12px;
                border: 2px solid $white;
                margin-left: 5px;  
            }
            #box-up {
                align-self: flex-start;
            }
        }
    }
}
</style>