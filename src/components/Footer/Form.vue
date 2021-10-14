<template>
    <!-- Form section with inputs  -->
    <section>
        <div class="container-80">
            <form action="">
                <div class="input-text-container">
                    <input type="text" placeholder="Your Name *">
                    <input type="text" placeholder="Your E-mail *">
                    <input type="text" placeholder="Subject">
                </div>
                <textarea cols="30" rows="10" placeholder="Your Message *"></textarea>
            </form>
            <div class="button">
                <button class="btn">SEND MESSAGE</button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Form'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/common';

.container-80 {
    form {
        display: flex;
        justify-content: space-between;
        margin: 40px 0 20px 0;
        .input-text-container {
            width: 49%;
            height: 100%;
            input[type=text]{
                display: block;
                padding: 15px 10px;
                width: 100%;
                border: 1px solid lightgray;
                margin-bottom: 15px;
            }
            ::placeholder {
                color: $grayText;
                font-size: 16px;
                font-weight: 600;
            }
        }
        textarea {
            width: 49%;
            height: 100%;
            border: 1px solid lightgray;
            padding: 10px;
        }
        ::placeholder {
            color: $grayText;
            font-size: 16px;
            font-weight: 600;
            padding: 5px;
            font-family: 'Roboto', sans-serif;
        }   
    }
    .button {
        display: flex;
        justify-content: center;
        .btn {
            @include orangeButton;
        }
        .btn:hover {
            background-color: $mainColor;
        }
    }
}
</style>