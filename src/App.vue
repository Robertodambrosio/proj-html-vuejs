<template>
  <div id="app">
    <Header :linkNav="linkNav"/>
    <Main/>
    <Footer :linkFoot="linkFoot"/>
  </div>
</template>

<script>
import Header from './components/macro/Header.vue'
import Main from './components/macro/Main.vue'
import Footer from './components/macro/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      linkNav: [
        {
          name: 'Home',
          arrow: false
        },
        {
          name: 'Landing',
          arrow: true
        },
        {
          name: 'Pages',
          arrow: true
        },
        {
          name: 'Docs',
          arrow: true
        }
      ],
      linkFoot: [
        {
          name: 'About us'
        },
                {
          name: 'Services'
        },
                {
          name: 'Team'
        },
                {
          name: 'Pricing'
        },
                {
          name: 'Project'
        },
                {
          name: 'Careers'
        },
                {
          name: 'Blog'
        },
                {
          name: 'Login'
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
