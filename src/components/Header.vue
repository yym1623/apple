<script>
import Header_inside from './Header_inside.vue';
export default {
  components: {
    Header_inside
  },
  data() {
    return {
      data: "",
      searchOpen: false,
      storeOpen: false
    }
  },
  methods: {
    search() {
      this.searchOpen = !this.searchOpen;
    },
    storr() {
      this.storeOpen = !this.storeOpen;
    }
  }
}
</script>


<template>
  <section class="container" :class="{ bg : data }">
    <div class="header">
      <div class="item apple">
        <img src="../svg/apple.svg" alt="">
      </div>
      <div class="item" @mouseover="data='store'">스토어</div>
      <div class="item" @mouseover="data='mac'">Mac</div>
      <div class="item" @mouseover="data='ipad'">iPad</div>
      <div class="item" @mouseover="data='iphone'">iPhone</div>
      <div class="item" @mouseover="data='watch'">Watch</div>
      <div class="item" @mouseover="data='airpods'">AirPode</div>
      <div class="item" @mouseover="data='tw'">TW 및 홈</div>
      <div class="item" @mouseover="data='enter'">엔터테인먼트</div>
      <div class="item" @mouseover="data='acc'">액세서리</div>
      <div class="item" @mouseover="data='service'">고객지원</div>
      <div class="item search" @click="search()">
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

    <!-- inside -->
    <Header_inside :event="data" @mouseleave="data=''" />

    <!-- search inside -->
    <div class="searchG" :class="{ searchOpen : searchOpen }">
      
    </div>
    <!-- store inside -->
    <div class="storeG" :class="{ storeOpen : storeOpen }">
      
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
    /* inside group */
    .searchG,
    .storeG {
      display: none;
      background: rgb(29, 29, 31);
      padding: 10px 30px 30px; 
      .searchIn,
      .storeIn {
        padding: 30px 0;
        max-width: 1000px;
        margin: auto;
        display: none;
        .group {
          display: flex;
        }
      }
    }
    .searchG.searchOpen {
      display: block;
    }
    .stpreG.storeOpen {

    }

  }
  .container.bg {
    background: rgb(29, 29, 31);
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