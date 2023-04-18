<script>
export default {
  props: {
    event: {
      type: String
    }
  }
}
</script>


<template>
  <div class="insides" :class="{ event : event }">
    <!-- 1 - store -->
    <div class="inside" :class="{ store : event === 'store' }">
      <div class="g">
        <div class="gt">쇼핑하기</div>
        <div>최신 제품 쇼핑하기</div>
        <div>MAC</div>
        <div>iPad</div>
        <div>iPhone</div>
        <div>Apple Watch</div>
        <div>액세서리</div>
      </div>
      <div class="g">
        <div class="gt">빠른 링크</div>
        <div>매장 찾기</div>
        <div>주문 상태</div>
        <div>금융 혜택</div>
        <div>Apple Trade In</div>
      </div>
      <div class="g">
        <div class="gt">특별 할인 쇼핑하기</div>
        <div>인증 리퍼비쉬 제품</div>
        <div>교육</div>
        <div>비즈니스</div>
      </div>
    </div>
    <!-- 2 - mac -->
    <div class="inside" :class="{ mac : event === 'mac' }">
      <div class="g">
        <div class="gt">Mac 살펴보기</div>
        <div>MacBook Air</div>
        <div>MacBook Pro</div>
        <div>iMac</div>
        <div>Mac mini</div>
        <div>Mac Studio</div>
        <div>Mac Pro</div>
        <div class="b">디스플레이</div>
        <div>Mac 비교하기</div>
        <div>Mac은 뭐든 척척</div>
        <div>Mac 모두 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">Mac 쇼핑하기</div>
        <div>Mac 쇼핑하기</div>
        <div>Mac 액세서리</div>
        <div>금융 혜택</div>
        <div>Apple Trade In</div>
      </div>
      <div class="g">
        <div class="gt">그 외 Mac 관련 항목</div>
        <div>Mac 지원</div>
        <div>macOS Ventura</div>
        <div>연속성</div>
        <div>iCloud</div>
        <div>Mac과 비즈니스</div>
        <div>교육</div>
      </div>
    </div>
    <!-- 3 - ipad -->
    <div class="inside" :class="{ ipad : event === 'ipad' }">
      <div class="g">
        <div class="gt">iPad 살펴보기</div>
        <div>iPad Pro</div>
        <div>iPad Air</div>
        <div>iPad</div>
        <div>iPad mini</div>
        <div>Apple Pencil</div>
        <div class="b">키보드</div>
        <div>iPad 비교하기</div>
        <div>iPad를 선택하는 이유</div>
        <div>iPad 모두 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">iPad 쇼핑하기</div>
        <div>iPad 쇼핑하기</div>
        <div>iPad 액세서리</div>
        <div>금융 혜택</div>
        <div>Apple Trade In</div>
      </div>
      <div class="g">
        <div class="gt">그 외 iPad 관련 항목</div>
        <div>iPad 지원</div>
        <div>iPadOS 16</div>
        <div>iCloud</div>
        <div>교육</div>
      </div>
    </div>
    <!-- 4 - iphone -->
    <div class="inside" :class="{ iphone : event === 'iphone' }">
      <div class="g">
        <div class="gt">iPhone14 Pro 살펴보기</div>
        <div>iPhone 14 Pro</div>
        <div>iPhone 14</div>
        <div>iPhone 13</div>
        <div>iPhone 12</div>
        <div class="b">iPhone SE</div>
        <div>iPhone 비교하기</div>
        <div>iPhone으로 갈아타기</div>
        <div>iPhone 모두 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">iPhone 쇼핑하기</div>
        <div>iPhone 쇼핑하기</div>
        <div>iPhone 액세서리</div>
        <div>Apple Trade In</div>
        <div>금융 혜택</div>
      </div>
      <div class="g">
        <div class="gt">그 외 iPhone 관련 항목</div>
        <div>iPhone 지원</div>
        <div>iOS 16</div>
        <div>iPhone의 개인 정보 보호</div>
        <div>iCloud</div>
        <div>Apple 지갑, Apple Pay</div>
        <div>Siri</div>
      </div>
    </div>
    <!-- 5 - watch -->
    <div class="inside" :class="{ watch : event === 'watch' }">
      <div class="g">
        <div class="gt">Watch 살펴보기</div>
        <div>Apple Watch Ultra</div>
        <div>Apple Watch Series 8</div>
        <div>Apple Watch SE</div>
        <div>Apple Watch Nike</div>
        <div class="b">Apple Watch Hermes</div>
        <div>Watch 비교하기</div>
        <div>Apple Watch를 선택하는 이유</div>
        <div>Apple Watch 모두 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">Watch 쇼핑하기</div>
        <div>Apple Watch 쇼핑하기</div>
        <div>Apple Watch Studio</div>
        <div>Apple Watch 밴드</div>
        <div>Apple Watch 액세서리</div>
        <div>금융 혜택</div>
        <div>Apple Trade In</div>
      </div>
      <div class="g">
        <div class="gt">그 외 Watch 관련 항목</div>
        <div>Apple Watch 지원</div>
        <div>watchOS 9</div>
      </div>
    </div>
    <!-- 6 - airpode -->
    <div class="inside" :class="{ airpods : event === 'airpods' }">
      <div class="g">
        <div class="gt">AirPode 살펴보기</div>
        <div>AirPode 2세대</div>
        <div>AirPode 3세대</div>
        <div>AirPode Pro 2세대</div>
        <div class="b">AirPode Max</div>
        <div>AirPode 비교하기</div>
        <div>AirPode 모두 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">Watch 쇼핑하기</div>
        <div>Apple Watch 쇼핑하기</div>
        <div>Apple Watch Studio</div>
        <div>Apple Watch 밴드</div>
        <div>Apple Watch 액세서리</div>
        <div>금융 혜택</div>
        <div>Apple Trade In</div>
      </div>
      <div class="g">
        <div class="gt">그 외 Watch 관련 항목</div>
        <div>Apple Watch 지원</div>
        <div>watchOS 9</div>
      </div>
    </div>
    <!-- 7 - tw -->
    <div class="inside" :class="{ tw : event === 'tw' }">
      <div class="g">
        <div class="gt">TV 및 홈 살펴보기</div>
        <div>Apple TV 4K</div>
        <div>TV 및 홈 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">TV 및 홈 쇼핑하기</div>
        <div>Apple TV 4K 쇼핑하기</div>
        <div>Siri Remote 쇼핑하기</div>
        <div>TV 및 홈 액세서리</div>
      </div>
      <div class="g">
        <div class="gt">그 외 TV 및 홈 관련 항목</div>
        <div>Apple TV 지원</div>
        <div>Apple TV 앱</div>
        <div>Apple TV+</div>
        <div>홈 앱</div>
        <div>Apple Music</div>
        <div>Siri</div>
        <div>AirPlay</div>
      </div>
    </div>
    <!-- 8 - enter -->
    <div class="inside" :class="{ enter : event === 'enter' }">
      <div class="g">
        <div class="gt">엔터테인먼트 살펴보기</div>
        <div>Apple One</div>
        <div>Apple TV+</div>
        <div>Apple Music</div>
        <div>Apple Arcade</div>
        <div>Apple Podcasts</div>
        <div>Apple Books</div>
        <div class="b">Apple Store</div>
        <div>엔터테인먼트 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">지원</div>
        <div>Apple TV+ 지원</div>
        <div>Apple Music 지원</div>
      </div>
    </div>
    <!-- 9 - acc -->
    <div class="inside" :class="{ acc : event === 'acc' }">
      <div class="g">
        <div class="gt">액세서리 쇼핑하기</div>
        <div>Mac</div>
        <div>iPad</div>
        <div>iPhone</div>
        <div>Apple Watch</div>
        <div>AirPods</div>
        <div class="b">TV 및 홈</div>
        <div>액세서리 모두 쇼핑하기</div>
      </div>
      <div class="g">
        <div class="gt">액세서리 살펴보기</div>
        <div>Apple 제작 정품</div>
        <div>Beats by Dr.Dre</div>
        <div>AirTag</div>
      </div>
    </div>
    <!-- 10 - service -->
    <div class="inside" :class="{ service : event === 'service' }">
      <div class="g">
        <div class="gt">지원 상황 살펴보기</div>
        <div>iPhone</div>
        <div>Mac</div>
        <div>iPad</div>
        <div>Watch</div>
        <div>AirPods</div>
        <div>Music</div>
        <div class="b">TV</div>
        <div>지원 상황 살펴보기</div>
      </div>
      <div class="g">
        <div class="gt">도움 받기</div>
        <div>커뮤니티</div>
        <div>보장 상태 확인하기</div>
        <div>수리</div>
        <div>문의하기</div>
      </div>
      <div class="g">
        <div class="gt">유용한 주제</div>
        <div>AppleCare+ 구입하기</div>
        <div>Apple ID 및 암호</div>
        <div>청구 및 구독</div>
        <div>나의 찾기</div>
        <div>손쉬운 사용</div>
      </div>
    </div>
    <!-- 11 - search -->
    <div class="inside">
      <div class="g">
        <input type="search" />
      </div>
      <div class="g">
        <div class="gt">빠른 링크</div>
        <div>Apple Store Online에서 쇼핑하기</div>
        <div>액세서리</div>
        <div>AirPods</div>
        <div>AirTag</div>
        <div>Apple Trade in</div>
      </div>
    </div>
    <!-- 12 - cart -->
    <div class="inside">
      <div class="g">
        <div>장바구니가 비어 있습니다.</div>
        <div>저장해둔 항목이 있는지 확인하려면 로그인하세요</div>
      </div>
      <div class="g">
        <div class="gt">내 프로필</div>
        <div>주문</div>
        <div>관심목록</div>
        <div>계정</div>
        <div>로그인</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .insides {
    display: none;
    background: rgb(29, 29, 31);
    padding: 10px 30px 30px; 
    .inside {
      display: none;
    }
  }
  .insides.event {
    display: block;
    .inside.store {
      display: block;
    }
    .inside.mac {
      display: block;
    }
    .inside.ipad {
      display: block;
    }
    .inside.iphone {
      display: block;
    }
    .inside.watch {
      display: block;
    }
    .inside.airpods {
      display: block;
    }
    .inside.tw {
      display: block;
    }
    .inside.enter {
      display: block;
    }
    .inside.acc {
      display: block;
    }
    .inside.service {
      display: block;
    }
  }
</style>