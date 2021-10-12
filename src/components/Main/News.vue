<template>
    <!-- News section  -->
    <section>
        <div class="container-80">
            <div class="title">
                <h1>What's New</h1>
                <h3>Keep up to date with the latest news</h3>
                <img src="../../assets/img/header_divider.png" alt="Divider">
            </div>
            <div class="news-container">
                <div class="news">
                    <div class="date">October 03, 2014</div>
                    <div class="image">
                        <img src="../../assets/img/blog_09-525x315.jpg" alt="Child">
                        <div class="number">42</div>
                    </div>
                    <h2>Drawing and Painting Lessons</h2>
                    <p>Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum [...]</p>
                    <hr>
                    <div class="icons">
                        <div class="icon">
                            <img src="../../assets/img/author.png" alt="Author">
                            <span>Anna Brown</span>
                        </div>
                        <div class="icon">
                            <img src="../../assets/img/category.png" alt="Category">
                            <span>Events, Fun</span>
                        </div>
                    </div>
                </div>            
                <div class="news">
                    <div class="date">October 03, 2014</div>
                    <div class="image">
                        <img src="../../assets/img/blog_10-300x180.jpg" alt="Children">
                        <div class="number">19</div>
                    </div>
                    <h2>Fall Parents Meeting Day</h2>
                    <p>Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum [...]</p>
                    <hr>
                    <div class="icons">
                        <div class="icon">
                            <img src="../../assets/img/author.png" alt="Author">
                            <span>Anna Brown</span>
                        </div>
                        <div class="icon">
                            <img src="../../assets/img/category.png" alt="Category">
                            <span>Dance, Education</span>
                        </div>
                    </div>
                </div>
                <div class="news">
                    <div class="date">October 03, 2014</div>
                    <div class="image">
                        <img src="../../assets/img/blog_08-300x180.jpg" alt="Child">
                        <div class="number">22</div>
                    </div>
                    <h2>Birthday in Kidergarten</h2>
                    <p>Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum [...]</p>
                    <hr>
                    <div class="icons">
                        <div class="icon">
                            <img src="../../assets/img/author.png" alt="Author">
                            <span>Anna Brown</span>
                        </div>
                        <div class="icon">
                            <img src="../../assets/img/category.png" alt="Category">
                            <span>Games, General</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="button">
                <button class="btn">GO TO BLOG <i class="fas fa-chevron-right"></i></button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'News'
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
    .news-container {
        display: flex;
        justify-content: space-between;
        color: $grayText;
        margin-top: 40px;
        .news {
            width: 32%;
            .date {
                padding-bottom: 20px;
                color: #AEAEAE;
            }
            .image {
                width: 100%;
                max-height: 289px;
                position: relative;
                img {
                    width: 100%;
                    height: 100%;
                }
                .number {
                    padding: 7px;
                    margin-bottom: 4px;
                    background-color: $secondColor;
                    border: none;
                    color: $white;
                    font-size: 20px;
                    position: absolute;
                    bottom: 0;
                    right: 0;
                }
            }
            h2 {
                color: $mainColor;
                padding: 20px 0;
                font-weight: 400;
            }
            p {
                font-weight: 500;
                padding-bottom: 20px;
            }
            hr {
                border: 1px solid lightgray;
            }
            .icons {
                display: flex;
                margin-top: 10px;
                .icon {
                    margin-right: 30px;
                    span {
                        margin-left: 5px;
                        color: #AEAEAE;
                    }
                }
            }
        }
    }
    .button {
        text-align: center;
        margin-top: 50px;
        .btn {
            padding: 15px 20px;
            background-color: $secondColor;
            border: none;
            color: $white;
            font-weight: bold;
            i {
                margin-left: 10px;
            }
        }
    } 
}
</style>