<script>
export default {
  
}
</script>


<template>
  <section class="container">
    <div class="header">
      <div class="item apple">
        <img src="../svg/apple.svg" alt="">
      </div>
      <div class="item">스토어</div>
      <div class="item">Mac</div>
      <div class="item">iPad</div>
      <div class="item">iPhone</div>
      <div class="item">Watch</div>
      <div class="item">AirPode</div>
      <div class="item">TW 및 홈</div>
      <div class="item">엔터테인먼트</div>
      <div class="item">액세서리</div>
      <div class="item">고객지원</div>
      <div class="item search">
        <img src="../svg/search.svg" alt="">
      </div>
      <div class="item store">
        <img src="../svg/store.svg" alt="" />
      </div>
    </div>
    
    <div class="mobile">
      <div class="item apple">
        <img src="../svg/apple.svg" alt="">
      </div>
      <div class="right-item">
        <div class="item search">
          <img src="../svg/search.svg" alt="">
        </div>
        <div class="item store">
          <img src="../svg/store.svg" alt="" />
        </div>
        <div class="item menu">
          <i class="fa-solid fa-bars"></i>
        </div>
      </div>
    </div>
  </section>
</template>


<style lang="scss" scoped>
  .container {
    position: fixed;
    z-index: 100;
    top: 0;
    width: 100%;
    height: 44px;
    margin: auto;
    background: rgba(22, 22, 23, .8);
    color: #eee;
    /* color: #eee; */
    .header {
      max-width: 1000px;
      width: 100%;
      height: 100%;
      padding: 0 22px;
      box-sizing: border-box;
      margin: auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      .item {
        font-family: 'Noto Sans KR', sans-serif;
        font-size: 12px;
        height: 100%;
        display: flex;
        align-items: center;
        padding: 0 9px;
        box-sizing: border-box;
        transition: .8s;
        cursor: pointer;
        &:hover {
          transition: .8s;
          color: rgba(255, 255, 255, 8);
        }
      }
    }
    .mobile {
      display: none;
      max-width: 1000px;
      width: 100%;
      height: 100%;
      padding: 0 8px;
      box-sizing: border-box;
      margin: auto;
      /* display: flex; */
      justify-content: space-between;
      align-items: center;
      .item {
        font-family: 'Noto Sans KR', sans-serif;
        font-size: 12px;
        height: 100%;
        display: flex;
        align-items: center;
        padding: 0 13px;
        box-sizing: border-box;
        transition: .8s;
        cursor: pointer;
        &:hover {
          transition: .8s;
          color: rgba(255, 255, 255, 8);
        }
      }
      .right-item {
        display: flex;
        align-items: center;
        .menu {
          i {
            font-size: 14px;
          }
        }
      }
    }
  }
  @media screen and (max-width: 833px) {
    .container {
      height: 48px;
      .header {
        display: none;
      }
      .mobile {
        display: flex;
      }
    }
  }

</style>