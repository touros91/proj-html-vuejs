<template>
    <section> 
        <div class="container-80">
            <div class="images">
                <div class="icon-up">
                    <img src="../../assets/img/slider_icon10.png" alt="">
                </div>
                <div class="icon-down">
                    <img src="../../assets/img/slider_icon14.png" alt="">
                </div>
                <div class="icon-up">
                    <img src="../../assets/img/slider_icon11.png" alt="">
                </div>
                <div class="icon-down">
                    <img src="../../assets/img/slider_icon12.png" alt="">
                </div>
                <div class="icon-up">
                    <img src="../../assets/img/slider_icon13.png" alt="">
                </div>
            </div>
            <div class="hero-center">
                <div class="titles">
                    <h2>Friendly Atmosphere</h2>
                    <h1>Welcoming Place</h1>
                    <h1 class="light">For Every Child</h1>
                    <button class="btn">BUY THIS THEME NOW</button>
                </div>
                <div class="kids-images">
                    <img src="../../assets/img/slider_slide2_img1.png" alt="Child">
                    <img id="background" src="../../assets/img/slider_slide2_img2.png" alt="Child">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    height: 600px;
    background-image: url('../../assets/img/slider_slide2_background.png');
    .container-80 {
        position: relative;
        .images {
            width: 85%;
            margin-left: auto;
            display: flex;
            height: 130px;
            position: absolute;
            top: 50px;
            left: 10%;
            .icon-down {
                display: flex;
                align-items: flex-end;
            }
        }
        .hero-center {
            display: flex;
            h2 {
                color: $secondColor;
                font-family: 'Shadows Into Light Two', cursive;
            }
            h1 {
                font-size: 40px;
                color: $mainColor;
                margin: 10px 0;
            }
            .light {
                font-weight: 100;
            }
            .btn {
                padding: 15px 20px;
                background-color: $secondColor;
                border: none;
                color: white;
                margin-top: 20px
            }
            .titles {
                top: 200px;
                position: absolute;
            }
            .kids-images {
                display: flex;
                max-width: 450px;
                position: absolute;
                top: 50px;
                left: 30%;
                img {
                    width: 100%;
                }
                #background {
                    height: 350px;
                }
            }
        }

    } 
}

</style>