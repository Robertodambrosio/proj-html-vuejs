<template>
    <div class="container mt-5 py-5">
        <div class="row">
            <div class="col-4">
                <img src="../../assets/img/logo-light.png" alt="logo landrick">
                <p class="pt-4 pb-2">Start working with Landrick that can
                    provide everything
                    you need to generate awareness, drive traffic,
                    connect</p>
                <div class="icon-container d-flex justify-content-between">
                    <div class="icon-box">
                        <i class="fab fa-facebook"></i></div>
                    <div class="icon-box">
                        <i class="fab fa-instagram"></i></div>
                    <div class="icon-box">
                        <i class="fab fa-twitter"></i> </div>
                    <div class="icon-box">
                        <i class="fab fa-linkedin"></i> </div>
                </div>
            </div>
            <div class="col-2">
                <ul>
                    <h4 class="pb-2">Company</h4>
                    <li v-for="(link, i) in linkFoot" :key="i"><i class="fas fa-chevron-right me-3"></i>{{link.name}}</li>
                </ul>
            </div>
            <div class="col-3">
                <ul>
                    <h4 class="pb-2">Usefull Links</h4>
                    <li ><i class="fas fa-chevron-right me-3"></i>Terms of Services</li>
                    <li><i class="fas fa-chevron-right me-3"></i>Privacy Policy</li>
                    <li><i class="fas fa-chevron-right me-3"></i>Documentation</li>
                    <li><i class="fas fa-chevron-right me-3"></i>Changelog</li>
                    <li><i class="fas fa-chevron-right me-3"></i>Components</li>
                </ul>
            </div>
            <div class="col-3">
                <h4 class="pb-2">Newsletter</h4>
                <p>Sign up and receive the latest tips via email.</p>
                <p>Write your email <span style="color: red; background: none">*</span></p>
                <div class="form-container mb-5">
                    <div class="input-group mb-3">
                        <span class="input-group-text"><i class="far fa-envelope"></i></span>
                        <input type="text" class="form-control p-2" placeholder="Your email:" aria-label="Your email:">
                    </div>
                    <button class="btn w-100" type="button">Subscribe</button>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterTop',
        props: {
            linkFoot: Array
    }
    }
</script>

<style lang="scss" scoped>
    img {
        width: 150px;
    }

    .icon-container {
        width: 40%;

        .icon-box {
            border: 1px solid white;
            border-radius: 10px;
            padding: 3px 7px;
        }
    }

    ul {
        list-style: none;


        li {
            line-height: 40px;
            color: #8492a6;
        }
    }

span{
    background-color: #27314f;
    color: white;
    border: none;
}

    input {
        background-color: #27314f;
        border: none;
    }

    button {
        background: #27314f;
         box-shadow: 1px 4px 3px #2f55d4;
         color: #2f55d4;
         font-weight: bold;
    }
    
</style>