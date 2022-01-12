<template>
    <div class="container py-5">
        <div class="text-container text-center ">
            <span style="color: #2f55d4">Quickstart</span>
            <h2 class="pt-2">Awesome isn't it? Let's dive in!</h2>
            <p class="pt-4 pb-5 mx-auto">Start working with <span style="color: #2f55d4">Landrick</span> that can
                provide everything
                you need to generate awareness, drive traffic,
                connect</p>
        </div>
        <div class="setup-container">
            <div class="row bg-dark text-light py-3 mb-2 w-100">
                <div class="col-11">
                    <div class="ul d-flex justify-content-md-around text-center">
                        <div class="li py-2 bg-dark">npm</div>
                        <div class="li py-2">nuget</div>
                        <div class="li py-2">spm</div>
                        <div class="li py-2">github</div>
                    </div>
                </div>
                <span class="py-3 px-4" style="color: #adb5bd"><span style="color: #2ec8ab">$</span> npm install <span
                        style="color: #2ec8ab">-g</span> claps.js</span>
            </div>
            <span class="me-4"><i class="far fa-check-circle mx-1" style="color: #2ec8ab"></i>Organize your
                data</span><span><i class="far fa-check-circle mx-1" style="color: #2ec8ab"></i>Work with any
                team</span>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Quickstart'
    }
</script>

<style lang="scss" scoped>
    .text-container p {
        max-width: 60%;
    }

    .setup-container {
        width: 65%;
        margin: 0 auto;


        .row {
            border-radius: 10px;
            width: 80%;
            margin: 0 auto;

            .col-11 {
                border: 1px solid #6d7277;
                border-radius: 10px;
                background-color: #3c4858;
                margin: 0 auto;
                padding: 0;

                .li {
                    width: 100%;
                    font-weight: bold
                }

                .li:first-child {
                    border-radius: 10px
                }


            }
        }
    }
</style>