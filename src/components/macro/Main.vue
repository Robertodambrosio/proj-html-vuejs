<template>
  <main>
    <Partner/>
    <Features/>
    <Quickstart/>
    <Tools/>
  </main>
</template>

<script>
import Tools from '../sections/Tools.vue'
import Quickstart from '../sections/Quickstart.vue'
import Features from '../sections/Features.vue'
import Partner from '../sections/Partner.vue'

export default {
    name: 'Main',
    components: {
      Partner,
      Features,
      Quickstart,
      Tools
    }
}
</script>

<style lang="scss" scoped>

</style>