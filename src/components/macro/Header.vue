<template>
  <header>
      <Navbar :linkNav="linkNav"/>
      <Jumbo/>
  </header>
</template>

<script>
import Navbar from '../sections/Navbar.vue'
import Jumbo from '../sections/Jumbo.vue'

export default {
    name: 'Header',
    props: {
        linkNav: Array
    },
    components: {
        Navbar,
        Jumbo
    }
}
</script>

<style lang="scss" scoped>
header{
    background-color: #f8f9fc;
    border-bottom: 1px solid rgb(230, 230, 230);
}
</style>