<template>
  <footer>
    <FooterTop/>
    <FooterBottom/>
  </footer>
</template>

<script>
import FooterBottom from '../sections/FooterBottom.vue'
import FooterTop from '../sections/FooterTop.vue'
export default {
  components: {
     FooterTop,
    FooterBottom 
  },
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
footer {
  background-color: #202942;;
  color: white;
}
</style>