<template>
    <div class="container py-5">
        <div class="text-container text-center">
            <h2 class="pt-2">Want to be among the first to find out</h2>
            <p class="pt-4 pb-5 mx-auto">
                Start working with <span style="color: #2f55d4">Landrick</span> that can
                provide everything you need to generate awareness, drive traffic,
                connect
            </p>
        </div>
        <div class="input mb-3">
            <input type="text" class="form-control py-3 ps-4" placeholder="Email address" aria-label="Email address"><button class="btn1 btn" type="button">Get started</button>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
@import '../../assets/style/variables.scss';

    .text-container p {
        max-width: 55%;
    }

    .input {
        position: relative;
        width: 55%;
        margin: 0 auto
    }

    input {
        border-radius: 30px;

    }

      .btn1 {
    background-color: $mainblue;
    color: white;
    font-weight: bold;
    padding: 8px 17px;
    border-radius: 30px;
    box-shadow: 1px 4px 3px #b9c8fa;
    position: absolute;
    top: 13%;
    right: 1%;
  }
</style>