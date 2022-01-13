<template>
  <footer>
    <FooterTop :linkFoot="linkFoot"/>
    <FooterBottom/>
  </footer>
</template>

<script>
import FooterBottom from '../sections/FooterBottom.vue'
import FooterTop from '../sections/FooterTop.vue'
export default {
  components: {
     FooterTop,
    FooterBottom,
  },
    name: 'Footer',
    props: {
        linkFoot: Array
    },
}
</script>

<style lang="scss" scoped>
footer {
  background-color: #202942;;
  color: white;
}
</style>