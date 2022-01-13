<template>
  <div class="border-top py-4 position-relative">
    <div class="container align-items-center">
      <span>Landrick. Design with ❤ by ShreeThemes.</span>
      <div class="card-container float-end">
        <img src="../../assets/img/visa.png" alt="visa">
        <img src="../../assets/img/paypal.png" alt="paypal">
        <img src="../../assets/img/master-card.png" alt="mastercard">
        <img src="../../assets/img/discover.png" alt="discover">
        <img src="../../assets/img/american-ex.png" alt="american-ex">
           <a href="#home"> <div class="tornasu float-end"><i class="fas fa-arrow-up"></i> </div></a>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'FooterBottom'
  }
</script>

<style lang="scss" scoped>
 @import '../../assets/style/variables.scss';

  .border-top {
    border-top: 1px solid #283353 !important;

    p {
      margin-bottom: 0
    }

    img {
      width: 30px;
      margin-right: 5px;
    }
    .tornasu {
      position: absolute;
      bottom: 15px;
      right: 30px;
      font-size:10px;
      z-index: 100000;
      background: $mainblue;
        padding: 10px 15px;
        border-radius: 5px;
        transition: 0.3s;
        color: white;
        font-size: 15px;
    }
  }
</style>