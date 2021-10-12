<template>
    <section>
        <div class="container-80">
            <div class="left-box">
                <h2>We have been educated children for over fifteen years. Our goals is to create a place that engages each child.</h2>
                <p>Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis facilisis venenatis aenean interdum.</p>
                <ul>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Comprehensive reporting on indvidual achievement</li>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Educational field trips and school presentations</li>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Individual attention in a small-class setting</li>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Learning program with after-school care</li>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Opportunities to carry out scientific investigations</li>
                    <li><img src="../../assets/img/style_1.png" alt="Orange Checkbox">Positive learning environment for your child</li>
                </ul>
            </div>
            <div class="right-box">
                <div class="icon-box">
                    <div class="icon">
                        <div class="image">
                            <img src="../../assets/img/toy.png" alt="Toy">
                        </div>
                        <h3>Learning & Fun</h3>
                        <p>Praesent modea est gravida node vehicula luctus.</p>
                    </div>
                    <div class="icon">
                        <div class="image">
                            <img src="../../assets/img/meal.png" alt="Meal">
                        </div>
                        <h3>Healthy Meals</h3>
                        <p>Terminal interdum a eleifend maecenas est morbi.</p>
                    </div>
                    <div class="icon">
                        <div class="image">
                            <img src="../../assets/img/school.png" alt="School">
                        </div>
                        <h3>Friendly Place</h3>
                        <p>Terminal interdum a eleifend maecenas est morbi.</p>
                    </div>
                    <div class="icon">
                        <div class="image">
                            <img src="../../assets/img/shield.png" alt="Shield">
                        </div>
                        <h3>Children Safety</h3>
                        <p>Praesent modea est gravida node vehicula luctus.</p>
                    </div>
                </div>
            </div>
        </div>


    </section>
</template>

<script>
export default {
    name: 'Goals'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

section {
    background-color: #F5F5F5;
    .container-80 {
        padding: 50px 0;
        display: flex;
        justify-content: space-between;
        .left-box, .right-box {
            width: 48%;
        }
        .left-box {
            h2 {
                color: $mainColor;
                font-weight: 400;
            }
            p {
                color: $grayText;
                margin: 40px 0;
                font-weight: 500;
            }
            ul li {
                list-style: none;
                margin-bottom: 15px;
                color: $grayText;
                font-weight: 500;
                img {
                    margin-right: 15px;
                }
            }
        }
        .right-box {
            .icon-box {
                display: flex;
                flex-wrap: wrap;
                .icon {
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    width: 50%;
                    margin-bottom: 20px;
                    h3 {
                        text-align: center;
                        color: $mainColor;
                        margin: 20px;
                        font-weight: 400;
                        font-size: 22px;
                    }
                    p {
                        color: $grayText;
                        font-weight: 500;
                        text-align: center;
                    }
                    .image {
                        border-radius: 50%;
                        margin: auto;
                        width: 90px;
                        height: 90px;
                        position: relative;
                        background-color: $white;
                        color: $white;
                        img {
                            padding: 5px;
                            width: 50%;
                            position: absolute;
                            top: 50%;
                            left: 50%;
                            transform: translate(-50%, -50%);        
                        }
                    }
                
                }
            }
        }
    }
}

</style>