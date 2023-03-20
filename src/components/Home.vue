<script>
export default {

}
</script>



<template>
  <div class="container">
    <div class="des">
      <div class="d">iPhone 7 Plus 이후 모델을 보상 판매하면 iPhone 14 또는 iPhone 14 Pro 구입 시 사용할 수 있는 ₩40,000 ₩780,000 상당의 크레딧의<a href="#">iPhone 쇼핑하기</a></div>
    </div>
    <div class="iphone i"></div>
    <div class="iphone-ug i"></div>
    <div class="watch i"></div>
  </div>
</template>


<style lang="scss" scoped>
  * {
    box-sizing: border-box;
  }
  .container {
    font-family: 'Noto Sans KR', sans-serif;
    margin-top: 44px;
    width: 100%;
    background: #fff;
    .des {
      color: #1D1D1F;
      background: #eee;
      width: 100%;
      height: 44px;
      font-size: 13px;
      margin: auto;
      font-weight: 600;
      padding: 15px 0;
      .d {
        /* max 하면서 기본 width도 100%로 해야 max이하로갈때 반응형으로 적용된단 -> max이상으로만 안가고 반응형 느낌 */
        /* 태블릿이난 모바일로 줄어들면서 반응형으로 위치 조정하면서 나머지 자잘한건 내려깎는 느낌 ㄱ */
        max-width: 850px;
        width: 100%;
        margin: auto;
        a {
          padding-left: 10px;
          color: #0066CC;
          text-decoration: none;
          &:hover {
            text-decoration: underline;
          }
        }
      }
    }
    .i {
      width: 100%;
      height: 730px;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      margin-top: 10px;
    }
    .iphone {
      background-image: url('/public/home(1).jpg');
      margin-top: 0;
    }
    .iphone-ug {
      background-image: url('/public/home(2).jpg');
    }
    .watch {
      background-image: url('/public/home(3).jpg');
    }
  }
  /* @media screen and (min-width: 1050px) {
    .container {
      .des {
        .d {
          max-width: 800px;
        }
      }
    }
  } */
</style>