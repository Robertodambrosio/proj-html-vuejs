<template>
  <div class="container mb-5">
    <nav class="row py-2">
      <div class="col-2">
        <img src="../../assets/img/logo-dark.png" alt="landrick logo">
      </div>
      <div class="col-8">
        <ul class="nav justify-content-center">
          <li class="nav-item" v-for="(link, i) in linkNav" :key="i">
            <a v-if="!link.arrow" class="nav-link mx-1" aria-current="page" href="#">{{link.name}}</a>
            <a v-else class="nav-link mx-1" aria-current="page" href="#">{{link.name}}<i class="fas fa-chevron-down mx-1"></i></a>
          </li>
        </ul>
      </div>
      <div class="col-2 icon">
          <div class="icon-first"><i class="fas fa-search"></i> </div>     
          <div class="icon-nav"><i class="fab fa-github"></i></div>       
          <div class="icon-nav"><i class="fab fa-stack-overflow"></i></div>           
          <div class="icon-nav"><i class="far fa-user"></i></div>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {
    name: 'Navbar',
    props: {
      linkNav: Array
    }
      
  }
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';

 .row {
   display: flex;
   align-items: center;

   img {
     width: 150px;
   }

    .nav-item{
      text-decoration: none;
      text-transform: uppercase;
      font-size: 13px;
      font-weight: 600;

      a {
        color: $maintext;
      }
    }

      
    .icon{
      display: flex;
      justify-content: space-around;
      color: $mainblue;

      .icon-first {
        color: #8492a6;
        padding: 5px 10px
      }

      .icon-nav{
        background: $bgi;
        padding: 5px 10px;
        border-radius: 5px;
        box-shadow: 1px 4px 3px #b9c8fa;

      &:hover {
        box-shadow: none;
        background: $mainblue;
        color: white;
        cursor: pointer;
      }
      }
    }

 }
</style>