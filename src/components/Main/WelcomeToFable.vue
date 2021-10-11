<template>
    <section>
        <div class="container-80">
            <div class="title">
                <h1>Welcome to Fable</h1>
                <h3>Fable daycare, preschool, and kindergarden</h3>
                <img src="../../assets/img/header_divider.png" alt="Divider">
            </div>
            <div class="icon-box">
                <div class="icon">
                    <div class="image">
                        <img src="../../assets/img/schoolbag_alt.png" alt="School Bag">
                    </div>
                    <h3>Morbi Etos</h3>
                    <p>Praesent interdum est gravida vehicula est node maecenas looaret morbi a dosis luctus novum est praesent.</p>
                </div>

                <div class="icon">
                    <div class="image violet">
                        <img src="../../assets/img/stroller_alt.png" alt="Stroller">
                    </div>
                    <h3>Congue Gravids</h3>
                    <p>Elipsis magna a terminal nulla elementum morbi elite forte maecenas est magna interdum vitae est.</p>
                </div>

                <div class="icon">
                    <div class="image">
                        <img src="../../assets/img/globe_alt.png" alt="Globe">
                    </div>
                    <h3>Maecenas Node</h3>
                    <p>Praesent interdum est gravida vehicula est node maecenas looaret morbi a dosis luctus novum est praesent.</p>
                </div>

                <div class="icon">
                    <div class="image violet">
                        <img src="../../assets/img/bell_alt.png" alt="Bell">
                    </div>
                    <h3>Praesent Morbi</h3>
                    <p>Elipsis magna a terminal nulla elementum morbi elite forte maecenas est magna interdum vitae est.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'WelcomeToFable'
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
    .icon-box {
        display: flex;
        margin-top: 50px;
        .icon {
            display: flex;
            flex-direction: column;
            justify-content: center;
            width: 25%;
            h3 {
                text-align: center;
                color: $mainColor;
                margin: 20px;
                font-weight: 400;
                font-size: 22px;
            }
            p {
                color: #7E7E7E;
                font-weight: 500;
                text-align: center;
            }
            .image {
                border-radius: 50%;
                margin: auto;
                width: 200px;
                height: 200px;
                position: relative;
                background-color: $secondColor;
                color: white;
                img {
                    position: absolute;
                    top: 50%;
                    left: 50%;
                    transform: translate(-50%, -50%);        
                }
            }
            .violet {
                background-color: $mainColor;
            }
        }
    } 
}


</style>