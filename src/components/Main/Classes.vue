<template>
    <section>
        <div class="container-80">
            <div class="title">
                <h1>Our Classes</h1>
                <h3>Our preschool program has four dedicated classes</h3>
                <img src="../../assets/img/header_divider.png" alt="Divider">
            </div>
            <div class="flex-container">
                <div class="box"><h2> We provided four classes with nine to twenty childrn each aged twelve month to five years of age.</h2></div>
                <div class="box"><p>Present arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eaget lacinia eleifend praesent luctus a arcu quis facilisi venenatis. Aenean interdum, nibh vitae sodales, magna ante feugiat elit maecenas.</p></div>
                <div class="box">
                    <div class="classes">
                        <div class="class-name">
                            <h3>Little Lambs</h3>
                            <h4 class="gray">Class name</h4>
                        </div>
                        <div class="class-info">
                            <div class="class-age">
                                <div class="text-center">12-24</div>
                                <div class="gray">Month olds</div>
                            </div>
                            <div class="class-size">
                                <div class="text-center">9</div>
                                <div class="gray">Class size</div>
                            </div>
                        </div>
                    </div>
                    <div class="image">
                        <img src="../../assets/img/gallery_04.jpg" alt="Kindergarten Class">
                        <button class="btn">READ MORE <i class="fas fa-chevron-right"></i></button>
                    </div>
                </div>
                <div class="box">
                    <div class="classes">
                        <div class="class-name">
                            <h3>Bouncy Bears</h3>
                            <h4 class="gray">Class name</h4>
                        </div>
                        <div class="class-info">
                            <div class="class-age">
                                <div class="text-center">2-3</div>
                                <div class="gray">Year olds</div>
                            </div>
                            <div class="class-size">
                                <div class="text-center">12</div>
                                <div class="gray">Class size</div>
                            </div>
                        </div>
                    </div>
                    <div class="image">
                        <img src="../../assets/img/class_02-690x506.jpg" alt="Kindergarten Class">
                        <button class="btn">READ MORE <i class="fas fa-chevron-right"></i></button>
                    </div>
                </div>
                <div class="box">
                    <div class="classes">
                        <div class="class-name">
                            <h3>Tenderhearts </h3>
                            <h4 class="gray">Class name</h4>
                        </div>
                        <div class="class-info">
                            <div class="class-age">
                                <div class="text-center">3-4</div>
                                <div class="gray">Year olds</div>
                            </div>
                            <div class="class-size">
                                <div class="text-center">15</div>
                                <div class="gray">Class size</div>
                            </div>
                        </div>
                    </div>
                    <div class="image">
                        <img src="../../assets/img/class_03-690x506.jpg" alt="Kindergarten Class">
                        <button class="btn">READ MORE <i class="fas fa-chevron-right"></i></button>
                    </div>
                </div>
                <div class="box">
                    <div class="classes">
                        <div class="class-name">
                            <h3>Shining Stars</h3>
                            <h4 class="gray">Class name</h4>
                        </div>
                        <div class="class-info">
                            <div class="class-age">
                                <div class="text-center">4-5</div>
                                <div class="gray">Year olds</div>
                            </div>
                            <div class="class-size">
                                <div class="text-center">20</div>
                                <div class="gray">Class size</div>
                            </div>
                        </div>
                    </div>
                    <div class="image">
                        <img src="../../assets/img/class_04-690x506.jpg" alt="Kindergarten Class">
                        <button class="btn">READ MORE <i class="fas fa-chevron-right"></i></button>
                    </div>
                </div>

            </div>
           
        </div>
    </section>
</template>

<script>
export default {
    name: 'Classes'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

.container-80 {
    padding: 50px 0;
    .title {
        text-align: center;
        h1 {
            color: $mainColor;
            font-size: 45px;
            font-weight: 300;
        }
        h3 {
            font-weight: 500;
            color: #BBBBBB;
            font-size: 17px;
            margin-top: 10px;
            margin-bottom: 35px;
        }
    }  
    .flex-container {
        display: flex;
        flex-wrap: wrap;
        margin-top: 50px;
        .box {
            width: calc(50% - 20px);
            margin: 10px 10px;
            background: $mainColor;
            display: flex;
            h2 {
                color: $mainColor;
                background-color: white;
                padding-bottom: 40px;
                font-weight: 400;
            }
            p {
                color: #7E7E7E;
                background-color: white;
                padding-bottom: 40px;
            }
            .classes {
                width: 50%;
                color: white;
                padding: 20px;
                display: flex;
                flex-direction: column;
                justify-content: space-between;
            }
            .image {
                width: 50%;
                position: relative;
                img {
                    width: 100%;
                    height: 100%;
                }
                .btn {
                    padding: 13px 18px;
                    background-color: $secondColor;
                    border: none;
                    color: white;
                    position: absolute;
                    bottom: 0;
                    right: 0;
                    i {
                        margin-left: 5px;
                    }
                }
            }
            .text-center {
                text-align: center;
            }
            .gray {
                color: #C8C6E0;
                margin-top: 5px;
            }
            .class-info {
                display: flex;
                justify-content: space-evenly;
                .class-age {
                    border-right: 1px solid white;
                    padding-right: 10px;
                }
            }
        }
    }
}
</style>