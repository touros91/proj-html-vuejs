<template>
  <div id="app">
    <Header :srcLogo="require('./assets/img/logo.png')" :altLogo="'Fable Logo'" :nav="menu"/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Main
  },
  data (){
        return {
            menu: [
                {
                  title: 'Home',
                  img: 'home.png',
                  imgWhite: 'home-2.png',
                  alt: 'Home' 
                },
                {
                  title: 'Pages',
                  img: 'document.png',
                  imgWhite: 'document-2.png',
                  alt: 'Pages'
                },
                {
                  title: 'Blog',
                  img: 'printer.png',
                  imgWhite: 'printer-2.png',
                  alt: 'Blog'
                },
                {
                    title: 'Shop',
                    img: 'cart.png',
                    imgWhite: 'cart-2.png',
                    alt: 'Shop'
                },
                {
                  title: 'Shortcodes',
                  img: 'lab.png',
                  imgWhite: 'lab-2.png',
                  alt: 'Shortcodes'
                },
                {
                  title: 'Support',
                  img: 'chat.png',
                  imgWhite: 'chat-2.png',
                  alt: 'Support'
                },
                {
                  title: 'Contact',
                  img: 'envelope.png',
                  imgWhite: 'envelope-2.png',
                  alt: 'Contact'
                }
            ]
        }
  }
}
</script>

<style lang="scss">
@import './assets/style/common';

</style>
