<template>
  <main>
    <Partner/>
    <Features/>
    <Quickstart/>
    <Tools/>
    <Rates/>
    <Form/>
  </main>
</template>

<script>
import Tools from '../sections/Tools.vue'
import Quickstart from '../sections/Quickstart.vue'
import Features from '../sections/Features.vue'
import Partner from '../sections/Partner.vue'
import Rates from '../sections/Rates.vue'
import Form from '../sections/Form.vue'

export default {
    name: 'Main',
    components: {
      Partner,
      Features,
      Quickstart,
      Tools,
      Rates,
      Form
    }
}
        
</script>

<style lang="scss" scoped>

</style>