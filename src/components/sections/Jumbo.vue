<template>
  <div class="container py-5">
      <div class="row align-items-center">
          <div class="col-6">
              <span>Development</span>
              <div class="container-text">
                  <h1>A Complete Developer Toolset</h1>
              </div>
                  <p class="py-3">Launch your campaign and benefit from our expertise on designing and managing conversion centred bootstrap 4 html page</p>
                  <button type="button" class="btn btn1 me-2">Get Started</button><button type="button" class="btn btn2">Documentation</button>
                  <p class="mt-3">Current version: v2.6.0</p>
          </div>
          <div class="col-6 text-center">
              <img src="../../assets/img/about.png" alt="about img">
          </div>
      </div>
  </div>
</template>

<script>
export default {
name: 
    'Jumbo'
}
</script>

<style lang="scss" scoped>
      span {
        background-color: #2f55d41a;
        padding: 3px 12px;
        border-radius: 20px;
        font-size: 12px;
        color: #2f55d4;
        font-weight: bold;
        border: 1px solid rgb(214, 214, 214);
    }
    .container-text {
        width: 60%;

        h1 {
            line-height: 60px;
            font-weight: bold;
        }
    }

        p {
            color: #adb5bd;
            font-weight: 600;
            max-width: 85%;
        }

        p:last-child {
            font-weight: 600;
        }

        .btn1{
            background-color: #2f55d4;
            color: white;
            font-weight: bold;
            padding: 8px 17px;
            border-radius: 8px;
            box-shadow: 1px 4px 3px #b9c8fa;
        }

        .btn2{
            border-color: #2f55d4;
            color: #2f55d4;
            font-weight: bold;
            padding: 8px 17px;
            border-radius: 8px;
        }
</style>