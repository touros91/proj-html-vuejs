<template>
    <footer>
        <GoogleMaps/>
        <section>
            <div class="container-80">
                <div class="title">
                    <h1>Contact Us</h1>
                    <h3>Our postal address and contact details</h3>
                    <img src="../../assets/img/header_divider.png" alt="Divider">
                </div>
            </div>
        </section>
        <ContactDetails :contactInfo="contacts"/>
    </footer>
</template>

<script>
import GoogleMaps from './GoogleMaps.vue';
import ContactDetails from './ContactDetails.vue';

export default {
    name: 'Footer',
    components: {
        GoogleMaps,
        ContactDetails
    },
    data() {
        return {
            contacts: [
                {
                    icon: 'document_orange.png',
                    name: 'Postal Address',
                    details: 'Fable Care Center 85 Fentiman Ave Ottawa, ON K1S 0T7'
                },
                {
                    icon: 'envelope_orange.png',
                    name: 'Phone & E-mail',
                    details: 'Phone: 1-800-64-38 Fax: 1-800-64-39 office@fable.com'
                },
                {
                    icon: 'mobile.png',
                    name: 'Business Hours',
                    details: 'Monday - Friday 8.00 am - 5.00 pm Weekend Closed'
                },
                {
                    icon: 'clock.png',
                    name: 'Sessions',
                    details: 'Mornings, 8 am - 12 noon Afternoons, 1 pm - 5 pm Full Day, 8 am - 5 pm'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

.container-80 {
    padding-top: 30px;
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
}
</style>