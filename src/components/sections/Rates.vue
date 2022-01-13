<template>
  <div class="container py-5">
    <div class="text-container text-center">
      <h2 class="pt-2">Our rates for developer from landrick team</h2>
      <p class="pt-4 pb-5 mx-auto">
        Start working with <span style="color: #2f55d4">Landrick</span> that can
        provide everything you need to generate awareness, drive traffic,
        connect
      </p>
    </div>
      <RatesCard/>
  </div>
</template>

<script>
import RatesCard from '../elements/RatesCard.vue'

export default {
    name: 'Rates',
    components: {
            RatesCard
        }
};
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';

.text-container p {
  max-width: 55%;
}

</style>