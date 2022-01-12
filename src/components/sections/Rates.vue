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
    <div class="card-container d-flex justify-content-between">
      <div class="card-1 p-4">
        <span class="initial-btn">Basic</span>
        <h2 class="mt-3">$9.00</h2>
        <p>Per month</p>
        <p>All the basics for businesses that are just getting started</p>
        <hr />
        <div class="ul">
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Full access
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Source Files
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >1 Domain Free
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
        </div>
        <button type="button" class="btn btn1 me-2 mt-3">Buy now</button>
        <p class="my-3">*No credit card required</p>
      </div>
      <div class="card-1 p-4">
        <span class="initial-btn mb-2">Business</span>
        <h2 class="mt-3">$39.00</h2>
        <p>Per month</p>
        <p>All the basics for businesses that are just getting started</p>
        <hr />
        <div class="ul">
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Full access
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Source Files
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >1 Domain Free
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
        </div>
        <button type="button" class="btn btn1 me-2 mt-3">Buy now</button>
        <p class="my-3">*No credit card required</p>
      </div>
      <div class="card-1 p-4">
        <span class="initial-btn mb-2">Enterprises</span>
        <h2  class="mt-3">$79.00</h2>
        <p>Per month</p>
        <p>All the basics for businesses that are just getting started</p>
        <hr />
        <div class="ul">
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Full access
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Source Files
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >1 Domain Free
          </p>
          <p class="li py-1">
            <i class="far fa-check-circle mx-1" style="color: #2f55d4"></i
            >Enhanced Security
          </p>
        </div>
        <button type="button" class="btn btn1 me-2 mt-3">Buy now</button>
        <p class="my-3">*No credit card required</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Rates'
};
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';


.text-container p {
  max-width: 55%;
}



.card-1 {
  width: 30%;
  box-shadow: 1px 4px 3px #b9c8fa;
  border: 1px solid #e9ecef;
  border-radius: 10px;


  .initial-btn {
  background-color: $bgi;
  padding: 3px 12px;
  border-radius: 20px;
  font-size: 12px;
  color: $mainblue;
  font-weight: bold;
  border: 1px solid rgb(214, 214, 214);
}

  .ul p {
    margin: 0;
  }

  .btn1 {
      width: 100%;
    background-color: $mainblue;
    color: white;
    font-weight: bold;
    padding: 8px 17px;
    border-radius: 8px;
    box-shadow: 1px 4px 3px #b9c8fa;
  }
}
</style>