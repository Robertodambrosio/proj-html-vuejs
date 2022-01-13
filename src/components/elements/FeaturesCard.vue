<template>
  <div class="feature-card">
    <div class="card" v-for="(feature, i) in features" :key="i">
      <div class="icon">
        <span class="icon-nav"><i :class="feature.icon"></i></span>
      </div>
      <span class="mt-5 mb-2 fw-bold">{{feature.title}}</span>
      <p>Composed in a pseudo-Latin language which more or less corresponds</p>
      <a class="pt-3">Read more<i class="fas fa-chevron-right mx-1"></i></a>
      <div class="icon-bg"><i :class="feature.icon"></i></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FeaturesCard",
  data() {
    return {
      features: [
        {
          title: "Modular",
          icon: "fas fa-layer-group",
        },
        {
          title: "Responsive",
          icon: "fas fa-tv icon",
        },
        {
          title: "Customizable",
          icon: "fas fa-crosshairs",
        },
        {
          title: "Scalable",
          icon: "fas fa-expand-arrows-alt",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";

.feature-card {
  display: flex;
  align-items: center;
  justify-content: space-between;

  .card {
    width: 23%;
    padding: 30px;
    border: 1px solid #e9ecef;
    border-radius: 10px;
    position: relative;
    transition: 0.2s;
    overflow: hidden;
    cursor: pointer;

    .icon {
      color: $mainblue;
      font-size: 20px;

      .icon-nav {
        background: $bgi;
        padding: 15px 20px;
        border-radius: 10px;
      }
    }

    a {
      text-decoration: none;
      color: $mainblue;
      font-weight: 400;
    }

    .icon-bg {
      position: absolute;
      top: 0;
      left: 70px;
      // width: 100%;
      // height: 100%;
      z-index: -1;
      opacity: 0;
      transition: opacity 0.4s;
      transform: scale(13);
      transform-origin: top left;
      color: $mainblue;
    }

    &:hover {
      .icon-bg {
        opacity: 0.05;
      }
    }
  }

  .card:hover {
    transform: translateY(-10px);
  }
}
</style>