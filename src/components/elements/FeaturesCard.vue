<template>
        <div class="feature-card">
          <div class="card card-1">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-layer-group"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Modular</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card card-2">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-tv icon"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Responsive</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card card-3">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-crosshairs"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Customizable</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
          <div class="card card-4">
              <div class="icon">
              <span class="icon-nav"><i class="fas fa-expand-arrows-alt mx-1"></i></span>
              </div>
              <span class="mt-5 mb-2 fw-bold">Scalable</span>
              <p>Composed in a pseudo-Latin language which more or less corresponds</p>
              <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
          </div>
      </div>
</template>

<script>
export default {
name: 'FeaturesCard'
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
        transition: top ease 0.5s;

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
    .card-1:hover,
    .card-2:hover,
    .card-3:hover,
    .card-4:hover {
    transform: translateY(-10px);
    cursor: pointer;
}
}

</style>