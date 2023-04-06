<script>
export default {
  components: {
    
  },

  data() {
    return {
      b__list__a: false,
      b__list__b: false,
      b__list__c: false,
      b__list__d: false,
      b__list__e: false,
      b__list__f: false,
      b__list__g: false,
      b__list__h: false,
      b__list__i: false,
    }
  },

  computed: {
    
  },

  methods: {
    footer_click(a) {
      switch(a) {
        case "a":
          this.b__list__a = !this.b__list__a;
          break;
        case "b":
          this.b__list__b = !this.b__list__b;
          break;
        case "c":
          this.b__list__c = !this.b__list__c;
          break;
        case "d":
          this.b__list__d = !this.b__list__d;
          break;
        case "e":
          this.b__list__e = !this.b__list__e;
          break;
        case "f":
          this.b__list__f = !this.b__list__f;
          break;
        case "g":  
          this.b__list__g = !this.b__list__g;
          break;
        case "h":
          this.b__list__h = !this.b__list__h;
          break;
        case "i":
          this.b__list__i = !this.b__list__i;      
          break;       
      }
    } 
  },
  mounted() {
  }
}
</script>


<template>
    <section class="container">
      <div class="footer">
        <div class="top">
          <div class="first">
            1. ₩780,000은 iPhone 13 Pro Max 1TB 모델의 보상 판매 금액으로, 보상 판매 금액은 보상 판매 대상이 되는 제품의 상태, 연도, 구성에 따라 달라집니다. 일부 기기는 보상 판매 대상이 아닙니다. 크레딧 또는 Apple Store Gift Card로 보상 판매를 받으려면 19세 이상이어야 합니다. 보상 판매 금액은 적용 가능한 새 기기 구입 시 적용하거나 Apple Store Gift Card로 받을 수 있습니다. 최종 확정 금액은 보상 판매 대상 기기를 수령한 후, 예상 금액 산정 시 제시한 기기의 설명과 일치하는지 비교 검수 후 정해집니다. 부가세는 새로 구입한 기기의 총액을 바탕으로 부과됩니다. 일부 매장에서는 보상 판매를 제공하지 않으며, 매장 내 보상 판매와 온라인 보상 판매 프로그램 간 내용에 차이가 있을 수 있습니다. 일부 매장은 추가 요구 사항이 있을 수 있습니다. Apple 또는 보상 판매 파트너사는 어떤 보상 판매도 거래를 거부하거나, 보상 판매 수량을 제한할 권리를 보유합니다. 적용 가능 기기의 보상 판매 및 재활용에 대한 자세한 내용은 Apple의 보상 판매 파트너사에서 확인할 수 있습니다. 규제 및 제한이 적용될 수 있습니다. 보상 판매 프로그램은 Apple의 파트너이자 독립적으로 운영되는 제3의 업체에 의해 제공됩니다. Apple 및 Apple의 계열사는 고객과 파트너 간 계약의 당사자가 아닙니다.
          </div>
          <div class="second">
            2. 무료 체험 기간이 끝나면 월 6,500원에 이용할 수 있습니다. 가족 공유 그룹당 하나의 멤버십 이용이 가능합니다. 무료 체험 혜택은 적용 대상 기기 활성화 이후 3개월 안에 신청할 수 있습니다. 멤버십은 매월 자동으로 갱신되며, 해지 시 종료됩니다. 특정 제한 사항 및 기타 약관이 적용됩니다.
          </div>
        </div>
        <div class="middle">
          <div class="s s1">
            <div class="b">
              <div class="b__f" @click="footer_click('a')">
                <div class="item title">쇼핑 및 알아보기</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__a :  b__list__a }">
                <div class="item"><span>스토어</span></div>
                <div class="item"><span>Mac</span></div>
                <div class="item"><span>iPad</span></div>
                <div class="item"><span>iPhone</span></div>
                <div class="item"><span>Watch</span></div>
                <div class="item"><span>AirPods</span></div>
                <div class="item"><span>TV 및 홈</span></div>
                <div class="item"><span>AirTag</span></div>
                <div class="item"><span>액세서리</span></div>
              </div>
            </div>
            <div class="b">
              <div class="b__f"  @click="footer_click('b')">
                <div class="item title p">Apple 지갑</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__b :  b__list__b }">
                <div class="item"><span>지갑</span></div>
                <div class="item"><span>Apple Pay</span></div>
              </div>
            </div>
          </div>
          <div class="s s2">
            <div class="b">
              <div class="b__f"  @click="footer_click('c')">
                <div class="item title">계정</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__c :  b__list__c }">
                <div class="item"><span>Apple ID 관리</span></div>
                <div class="item"><span>Apple Store 계정</span></div>
                <div class="item"><span>iCloud.com</span></div>
              </div>
            </div>
            <div class="b">
              <div class="b__f"  @click="footer_click('d')">
                <div class="item title p">엔터테인먼트</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__d :  b__list__d }">
                <div class="item"><span>Apple One</span></div>
                <div class="item"><span>Apple TV+</span></div>
                <div class="item"><span>Apple Music</span></div>
                <div class="item"><span>Apple Arcade</span></div>
                <div class="item"><span>Apple Podcasts</span></div>
                <div class="item"><span>Apple Books</span></div>
                <div class="item"><span>App Store</span></div>
              </div>
            </div>
          </div>
          <div class="s s3">
            <div class="b">
              <div class="b__f"  @click="footer_click('e')">
                <div class="item title">Apple Store</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__e :  b__list__e }">
                <div class="item"><span>매장 찾기</span></div>
                <div class="item"><span>Genius Bar</span></div>
                <div class="item"><span>Today at Apple</span></div>
                <div class="item"><span>Apple 캠프</span></div>
                <div class="item"><span>Apple Store 앱</span></div>
                <div class="item"><span>인증 리퍼비쉬 제품</span></div>
                <div class="item"><span>금융 혜택</span></div>
                <div class="item"><span>Apple Trade In</span></div>
                <div class="item"><span>주문 상태</span></div>
                <div class="item"><span>쇼핑 도움말</span></div>
              </div>
            </div>
          </div>
          <div class="s s4">
            <div class="b">
              <div class="b__f"  @click="footer_click('f')">
                <div class="item title">비즈니스</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__f :  b__list__f }">
                <div class="item"><span>Apple과 비즈니스</span></div>
                <div class="item"><span>비즈니스를 위한 제품 쇼핑하기</span></div>
              </div>
            </div>
            <div class="b">
              <div class="b__f"  @click="footer_click('g')">
                <div class="item title p">교육</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__g :  b__list__g }">
                <div class="item"><span>Apple과 교육</span></div>
                <div class="item"><span>초중고용 제품 쇼핑하기</span></div>
                <div class="item"><span>대학 생활을 위한 제품 쇼핑하기</span></div>
              </div>
            </div>
          </div>
          <div class="s s5">
            <div class="b">
              <div class="b__f"  @click="footer_click('h')">
                <div class="item title">Apple의 가치관</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__h :  b__list__h }">
                <div class="item"><span>손쉬운 사용</span></div>
                <div class="item"><span>교육</span></div>
                <div class="item"><span>환경</span></div>
                <div class="item"><span>개인정보 보호</span></div>
                <div class="item"><span>협력업체에 대한 책임</span></div>
              </div>
            </div>
            <div class="b">
              <div class="b__f"  @click="footer_click('i')">
                <div class="item title p">Apple 정보</div>
                <div class="m__p">+</div>
              </div>
              <div class="b__list" :class="{  b__list__i :  b__list__i }">
                <div class="item"><span>Newsroom</span></div>
                <div class="item"><span>Apple 리더</span></div>
                <div class="item"><span>채용 안내</span></div>
                <div class="item"><span>윤리 및 규정 준수</span></div>
                <div class="item"><span>이벤트</span></div>
                <div class="item"><span>일자리 창출</span></div>
                <div class="item"><span>Apple 연락처</span></div>
              </div>
            </div>
          </div>
        </div>
        <div class="bottom">
          <div class="f f1">다양한 쇼핑 방법: <a href="#">Apple Store를 방문하거나</a>, <a href="#">리셀러</a>를 찾아보거나, 000-000-0000번으로 전화하세요.</div>
          <div class="f f2 ">
            <div class="fitem fi1">Copyright © 2023 Apple Inc. 모든 권리 보유.</div>
            <div class="fitem fi2">
              <a href="#">개인정보 처리방침</a>
              <a href="#">웹 사이트 이용 약관</a>
              <a href="#">판매 및 환불</a>
              <a href="#">법적 고지</a>
              <a href="#">사이트 맵</a>
            </div>
            <div class="fitem fi3">대한민국</div>
          </div>
          <div class="f f3">
            사업자등록번호 : 000-00-00000 | 통신판매업신고번호 : 제 2023-서울-00000호 | 대표이사 : YOON YOUNGMIN | 주소 : 경기도 수원역 1번출구 | 대표전화 : 00-0000-0000 | 팩스 : 00-0000-0000
          </div>
        </div>
      </div>
    </section>
</template>


<style lang="scss" scoped>
  * {
    font-family: 'Nanum Gothic', sans-serif;
    box-sizing: border-box;
  }
  .container {
    color: #6E6E73;
    background: #F5F5F7;
    width: 100%;
    /* height: 100%; */
    /* height: 700px; */
    margin: auto;
    .footer {
      max-width: 1000px;
      width: 100%;
      height: 100%;
      margin: auto;
      font-size: 11px;
      padding: 0 22px;
      .top {
        position: relative;
        padding: 17px 0 11px;
        font-weight: 500;
        .first {
          padding-bottom: 10px;
          line-height: 1.5;
        }
        .second {
          padding-bottom: 10px;
          box-sizing: border-box;
          line-height: 1.5;
        }
        &::after {
          position: absolute;
          content: "";
          width: 100%;
          height: 1px;
          background: #d2d2d7;
        }
      }
      .middle {
        padding-top: 20px;
        display: flex;
        .s {
          flex-basis: 25%;
          font-weight: 500;
          .b {
            .b__f {
              display: block;
              .m__p {
                display: none;
              }
              .title {
                font-weight: bold;
                /* nth는 처음 들어간 부모클래스부터 시작한단 */
                color: #1D1D1F;
                margin-bottom: 20px !important;
                font-size: 12px;
              }
              .p {
                padding-top: 25px;
              }
            }
            .b__list {
              .item {
                margin-right: 20px;
                margin-bottom: 15px;
                color: #424245;
                span {
                  &:hover {
                    cursor: pointer;
                    text-decoration: underline;
                  }
                }
              }
            }
          }
        }
      }
      .bottom {
        padding: 35px 0 20px;
        .f {
          a {
            color: #0066CC;
          }
        }
        .f1 {
          position: relative;
          padding-bottom: 8px;
          margin-bottom: 8px;
          &::before {
            content: "";
            position: absolute;
            bottom: 0;
            background: #d2d2d7;
            width: 100%;
            height: 1px;
            /* background */
          }
        }
        .f2 {
          display: flex;
          margin-bottom: 8px;
          .fi1 {
            margin-right: 30px;
          }
          .fi2 {
            display: flex;
            a {
              text-decoration: none;
              position: relative;
              color: #424245;
              margin-left: 20px;
              &::before {
                content: "";
                position: absolute;
                left: -10px;
                height: 100%;
                width: 1px;
                background: #d2d2d7;;
              }
              &:first-child {
                margin-left: 0;
              }
              &:first-child::before {
                display: none;
              }
              &:hover {
                text-decoration: underline;
              }
            }
          }
          .fi3 {
            margin-left: auto;
          }
        }
        .f3 {
          font-size: 11px;
        }
      }
    }
  }
  @media screen and (max-width: 833px) {
    .container {
      .footer {
        .middle {
          display: block;
          .s {
            .b {
              position: relative;
              .b__f {
                display: flex;
                justify-content: space-between;
                align-items: center;
                cursor: pointer;
                .title {
                  display: block !important;
                  margin-bottom: 0 !important;
                  padding: 13px 0 !important;
                }
                .p {
                  padding-top: 0;
                }
                .m__p {
                  display: block;
                  font-size: 15px;
                  padding-right: 5px;

                }
              }
              .b__list {
                display: none;
                padding: 5px 0 16px;
                .item {
                  margin-right: 0;
                  padding: 6px 14px;
                  font-size: 11px;
                }
              }
              .b__list__a,
              .b__list__b,
              .b__list__c,
              .b__list__d,
              .b__list__e,
              .b__list__f,
              .b__list__g,
              .b__list__h,
              .b__list__i  {
                display: block;
              }


              &::after {
                position: absolute;
                content: "";
                width: 100%;
                height: 1px;
                background: #d2d2d7;;
              }
            }
          }
        }
        .bottom {
          .f2 {
            display: block;
            line-height: 2;
          }
          .f3 {
            line-height: 1.5;
          }
        }
      }
    }
  }

  @media screen and (max-width: 900px) {
    .container {
      .footer {
        .middle {
          font-size: 10px;
        }
      }
    }
  }
</style>