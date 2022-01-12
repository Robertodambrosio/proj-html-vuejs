<template>
    <div class="partner-bg py-5">
        <div class="container">
            <div class="partner-container">
                <img src="../../assets/img/amazon.svg" alt="amazon logo">
                <img src="../../assets/img/google.svg" alt="google logo">
                <img src="../../assets/img/lenovo.svg" alt="lenovo logo">
                <img src="../../assets/img/paypal.svg" alt="paypal logo">
                <img src="../../assets/img/shopify.svg" alt="shopify logo">
                <img src="../../assets/img/spotify.svg" alt="spotify logo">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Partner'
    }
</script>

<style lang="scss" scoped>
    .partner-bg {
        background-color: #f8f9fc;
        border-bottom-left-radius: 50%;
        border-bottom-right-radius: 50%;
        width: 100%;


        .partner-container {
            display: flex;
            align-items: center;
            justify-content: space-around;


            img {
                width: 90px;
            }
        }
    }
</style>