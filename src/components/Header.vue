<template>
    <header>
        <div class="container-80">
            <div class="logo">
                <img :src="srcLogo" :alt="altLogo">
            </div>
            <div class="nav-menu">
                <ul>
                    <li v-for="(icon, index) in nav" :key="index">
                        <div class="icon-image">
                            <img :src="require('../assets/img/' + icon.img)" :alt="icon.alt">
                        </div>
                        <div class="icon-image-white">
                            <img :src="require('../assets/img/' + icon.imgWhite)" :alt="icon.alt">
                        </div> 
                        <div>{{icon.title}}</div>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
    props: ['srcLogo', 'altLogo', 'nav']
}
</script>

<style lang="scss" scoped>
@import '../assets/style/common';

header {
    font-size: 15px;
    .container-80 {
        display: flex;
        justify-content: space-between;
        .logo {
            max-width: 160px;
            img {
                width: 100%;
            }
        }
        .nav-menu {
            width: 70%;
            display: flex;
            justify-content: flex-end;
            ul {
                display: flex;
                li {
                    list-style: none;
                    display: inline-block;
                    padding: 30px;
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    color: $mainColor;
                    .icon-image, .icon-image-white {
                        max-width: 30px;
                        margin-bottom: 10px;
                        img {
                            width: 100%;
                        }
                    }
                    .icon-image-white {
                        display: none;
                    }
                }
                li:hover {
                    background-color: #FE6500;
                    color: white;
                }
                li:hover .icon-image {
                    display: none;
                }
                li:hover .icon-image-white {
                    display: block;
                }
            }
        }   
    }
}
</style>