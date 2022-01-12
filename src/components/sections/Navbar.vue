<template>
  <div class="container mb-5">
    <nav class="row py-2">
      <div class="col-2">
        <img src="../../assets/img/logo-dark.png" alt="landrick logo">
      </div>
      <div class="col-8">
        <ul class="nav justify-content-center">
          <li class="nav-item">
            <a class="nav-link mx-1" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: #2f55d4">Landing<i class="fas fa-chevron-down mx-1"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">Pages<i class="fas fa-chevron-down mx-1"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link ">Docs<i class="fas fa-chevron-down mx-1"></i></a>
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
    name: 'Navbar'
  }
</script>

<style lang="scss" scoped>
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
        color: #8492a6;
      }
    }

      
    .icon{
      display: flex;
      justify-content: space-around;
      color: #2f55d4;

      .icon-first {
        color: #8492a6;
        padding: 5px 10px
      }

      .icon-nav{
        background: #2f55d41a;
        padding: 5px 10px;
        border-radius: 5px;
        box-shadow: 1px 4px 3px #b9c8fa;

      &:hover {
        box-shadow: none;
        background: #2f55d4;
        color: white;
        cursor: pointer;
      }
      }
    }

 }
</style>