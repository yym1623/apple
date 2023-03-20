<script>
export default {

}
</script>


<template>
  <div class="container">
    <div class="iphone i"></div>
    <div class="iphone-ug i"></div>
    <div class="watch i"></div>
  </div>
</template>


<style lang="scss" scoped>
  .container {
    margin-top: 44px;
    width: 100%;
    background: #fff;
    .i {
      width: 100%;
      height: 730px;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      margin-top: 10px;
      &:first-child {
        margin-top: 0;
      }
    }
    .iphone {
      background-image: url('/public/home(1).jpg');
    }
    .iphone-ug {
      background-image: url('/public/home(2).jpg');
    }
    .watch {
      background-image: url('/public/home(3).jpg');
    }
  }
</style>