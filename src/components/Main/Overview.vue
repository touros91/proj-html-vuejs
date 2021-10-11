<template>
    <section>
        <div class="container-80">
            <div class="overview-info">
                <button class="btn-active">Overview</button>
                <button class="btn-unactive">Our Mission</button>
                <div class="title">
                    <h2>Our philosophy is learning through play as we offer a stimulating environment for children.</h2>
                </div>
                <div class="description">
                    <div class="image">
                        <img src="../../assets/img/clock_alt.png" alt="Clock">
                    </div>
                    <div class="info">
                        <h3>Full Day Sessions</h3>
                        <p>Pulvinar est metro ligula blandit maecenas retrum gravida cuprum. Maecenas node estibulum.</p>
                    </div>
                </div>
                <div class="description">
                    <div class="image">
                        <img src="../../assets/img/diagram_alt.png" alt="Diagram">
                    </div>
                    <div class="info">
                        <h3>Varied Classes</h3>
                        <p>Pulvinar est metro ligula blandit maecenas retrum gravida cuprum. Maecenas node estibulum.</p>
                    </div>
                </div>
            </div>
            <div class="images">
                <div class="current-image">
                    <img src="../../assets/img/gallery_08-690x506.jpg" alt="Kindergarten">
                    <div class="arrow-left">
                        <img src="../../assets/img/slider_previous.png" alt="Arrow left">
                    </div>
                    <div class="arrow-right">
                        <img src="../../assets/img/slider_next.png" alt="Arrow right">
                    </div>
                </div>
                <div class="unactive-images">
                    <div class="image">
                        <img src="../../assets/img/gallery_07-690x506.jpg" alt="Kindergarten">
                    </div>
                    <div class="image">
                        <img src="../../assets/img/gallery_01.jpg" alt="Kindergarten">
                    </div>
                    <div class="image">
                        <img src="../../assets/img/gallery_08-690x506.jpg" alt="Kindergarten">
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'Overview'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    background-color: #F5F5F5;
    padding: 30px 0;
    .container-80 {
        display: flex;
        .overview-info {
            width: 50%;
            .btn-active {
                padding: 13px 20px;
                background-color: $secondColor;
                border: none;
                color: $white;
                margin-top: 20px;
                font-size: 18px;
            }
            .btn-unactive {
                padding: 13px 20px;
                border: none;
                color: #BBBBBB;
                margin-top: 20px;
                font-size: 18px;
                margin-left: 15px;
            }
            .title {
                width: 85%;
                h2 {
                    color: $mainColor;
                    font-size: 25px;
                    font-weight: 400;
                    margin: 50px 0 30px 0;
                }   
            }
            .description {
                display: flex;
                justify-content: space-between;
                margin-bottom: 30px;
                .image {
                    width: 75px;
                    height: 75px;
                    border-radius: 50%;
                    padding: 22px;
                    background-color: $secondColor;
                    img {
                        width: 100%;
                    }
                }
                .info {
                    width: 80%;
                    h3 {
                        color: $mainColor;
                        margin-bottom: 20px;
                        font-weight: 400;
                        font-size: 22px;
                    }
                    p {
                        color: #7E7E7E;
                        font-weight: 400;
                    }
                }
            }
        }
        .images {
            width: 50%;
            padding: 20px;
            .current-image {
                width: 500px;
                margin-bottom: 5px;
                position: relative;
                img {
                    width: 100%;
                }
                .arrow-left, .arrow-right {
                    width: 40px;
                    background-color: $secondColor;
                    position: absolute;
                    img {
                        width: 100%;
                    }
                }
                .arrow-left {
                    top: 50%;
                    left: 0;
                }
                .arrow-right {
                    top: 50%;
                    right: 0;
                }
            }
            .unactive-images {
                width: 500px;
                display: flex;
                justify-content: space-between;
                .image {
                    width: 160px;
                    padding-bottom: 5px;
                    img {
                        width: 100%;
                    }
                }
            }
            .unactive-images .image:first-child {
                border-bottom: 2px solid $secondColor;
            }
            .unactive-images .image:hover{
                border-bottom: 2px solid $secondColor;
            }
        }
    }
}

</style>