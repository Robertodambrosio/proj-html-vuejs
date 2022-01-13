<template>
    <div class="container my-5">
        <div class="row title-features">
            <div class="col-7">
                <h2>Key Features</h2>
                <p class="py-4">Start working with <span style="color: #2f55d4">Landrick</span> that can provide
                    everything you need to generate awareness, drive traffic, connect.</p>
            </div>
        </div>
        <FeaturesCard />
    </div>
</template>

<script>
    import FeaturesCard from '../elements/FeaturesCard.vue'
    export default {


        name: 'Features',
        components: {
            FeaturesCard
        }
    }
</script>

<style lang="scss" scoped>
    @import '../../assets/style/variables.scss';
</style>