<template>
  <div class="container my-5">
      <div class="row title-features">
          <div class="col-7">
          <h2>Key Features</h2>
          <p class="py-4">Start working with <span style="color: #2f55d4">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</p>
          </div>
      </div>
      <div class="feature-card">
          <div class="card">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-layer-group"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Modular</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-tv icon"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Responsive</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-crosshairs"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Customizable</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-expand-arrows-alt mx-1"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Scalable</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
      </div>

  </div>
</template>

<script>
export default {
name: 'Features'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';

.feature-card {
    display: flex;
    align-items: center;
    justify-content: space-between;

    .card {
        width: 23%;
        padding: 30px;
        border: 1px solid #e9ecef;
        border-radius: 10px;

        .icon {
            color: $mainblue;
            font-size: 20px;

        .icon-nav{
            background: $bgi;
            padding: 15px 20px;  
            border-radius: 10px;      
            }
        }

        a{
            text-decoration: none;
            color: $mainblue;
            font-weight: 400;
        }
    }
}
</style>