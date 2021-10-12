<template>
    <section>
        <div class="container-80">
            <div class="icon-box">
                <div class="icon" v-for="(contact, index) in contactInfo" :key="index">
                    <div class="image">
                        <img :src="require('../../assets/img/' + contact.icon)" :alt="contact.name">
                    </div>
                    <h3>{{contact.name}}</h3>
                    <p>{{contact.details}}</p>
                </div>
            </div>
        </div> 
    </section>
</template>

<script>
export default {
    name: 'ContactDetails',
    props: ['contactInfo']
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';
section {
    padding: 10px 0;
    .container-80 {
        .icon-box {
            display: flex;
            margin: 20px 0;
            .icon {
                display: flex;
                flex-direction: column;
                justify-content: center;
                padding: 10px;
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
</style>