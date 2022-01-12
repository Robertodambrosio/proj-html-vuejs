<template>
    <div class="container py-5">
        <div class="row align-items-center">
            <div class="col-6">
                <div class="container-text">
                    <h2>Build tools and extensive documentation</h2>
                </div>
                <p class="py-3 mainp">You can combine all the Landrick templates into a single one, you can take a
                    component from the Application theme and use it in the Website</p>
                <div class="ul">
                    <p class="li"><i class="far fa-check-circle mx-1" style="color: #2f55d4;"></i> Marketin Solutions
                        for Tomorrow</p>
                    <p class="li"><i class="far fa-check-circle mx-1" style="color: #2f55d4;"></i> Our Talented &
                        Experienced Marketing Agency</p>
                    <p class="li"><i class="far fa-check-circle mx-1" style="color: #2f55d4;"></i> Create your own skin
                        to match your brand</p>
                </div>
                <button type="button" class="btn btn1 me-2 mt-3">Read more <i class="fas fa-arrow-right mx-1" style="color: #fff;"></i></button>
            </div>
            <div class="col-6 text-left">
                <img src="../../assets/img/1.png" alt="about img">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Tools'
    }
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';

    h2 {
        max-width: 70%;
    }

    .mainp {
        max-width: 90%;
    }

    .btn1 {
        background-color: $mainblue;
        color: white;
        font-weight: bold;
        padding: 8px 17px;
        border-radius: 8px;
        box-shadow: 1px 4px 3px #b9c8fa;
    }

img {
    width: 90%;
}

</style>