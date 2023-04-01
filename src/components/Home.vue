<script>
export default {

}
</script>



<template>
  <div class="container">
    <div class="des">
      <div class="d">iPhone 7 Plus 이후 모델을 보상 판매하면 iPhone 14 또는 iPhone 14 Pro 구입 시 사용할 수 있는 ₩40,000 ₩780,000 상당의 크레딧의<a href="#">iPhone 쇼핑하기</a></div>
    </div>
    <div class="iphone i">
      <div class="f">
        <div class="fitem f-a">Pay</div>
        <div class="fitem f-b">
          <div>카드 없이. 현금 없이. 오늘부터 바로.</div>
          <!-- <div class="b">이제 노랗게 물든 봄처럼</div> -->
        </div>
        <div class="fitem f-c f-one"><span>더 알아보기</span></div>
      </div>
    </div>
    <div class="iphone-ug i">
      <div class="f">
        <div class="fitem f-a">iPhone 14 Pro</div>
        <div class="fitem f-b">
          <div>프로 그 이상.</div>
        </div>
        <div class="fitem f-c">
          <div class="c">더 알아보기</div>
          <div class="c">구입하기</div>
        </div>
      </div>
    </div>
    <div class="watch i">
      <div class="f">
        <div class="fitem f-a">iPhone 14</div>
        <div class="fitem f-b">
          <div>두 가지 매력적인 사이즈.</div>
          <div class="b">이제 노랗게 물든 봄처럼.</div>
        </div>
        <div class="fitem f-c">
          <div class="c">더 알아보기</div>
          <div class="c">구입하기</div>
        </div>
      </div>
    </div>
    <div class="gbox">
      <div class="g g-a">
        <video id="vid" class="video" autoplay loop muted src="https://www.apple.com/105/media/kr/home/2023/1ec9a843-f35e-4273-9899-7ac71c60114e/anim/hero/mediumtall.mp4" data-inline-media-plugins="PlayPauseButton" aria-hidden="true">
        </video>
        <div class="f">
          <div class="fitem f-a">Apple 강남</div>
          <div class="fitem f-b">
            <div>3월 31일 오후 5시 오픈</div>
          </div>
          <div class="fitem f-c f-one"><span>더 알아보기</span></div>
        </div>
      </div>
      <div class="g g-b">
        <div class="f">
          <div class="fitem f-a">WATCH</div>
          <div class="fitem f-a-a">SERIES 8</div>
          <div class="fitem f-b">
            <div>건강하게 앞서 나아가다.</div>
          </div>
          <div class="fitem f-c">
            <div class="c">더 알아보기</div>
            <div class="c">구입하기</div>
          </div>
        </div>
      </div>
      <div class="g g-c">
        <div class="f">
          <div class="fitem f-a">iPad</div>
          <div class="fitem f-b">
            <div>쓰다. 그리다. 빠져들다.</div>
          </div>
          <div class="fitem f-c">
            <div class="c">더 알아보기</div>
            <div class="c">구입하기</div>
          </div>
        </div>
      </div>
      <div class="g g-d">
        <div class="f">
          <div class="fitem f-a">MacBook</div>
          <div class="fitem f-b">
            <div>막강한 성능의 M2 Pro 또는 M2 Max칩 탑재</div>
          </div>
          <div class="fitem f-c">
            <div class="c">더 알아보기</div>
            <div class="c">구입하기</div>
          </div>
        </div>
      </div>
      <div class="g g-e">
        <div class="f">
          <div class="fitem f-a">AirPods Pro</div>
          <div class="fitem f-b">
            <div>듣는다는 것을 다시 생각하다</div>
          </div>
          <div class="fitem f-c">
            <div class="c">더 알아보기</div>
            <div class="c">구입하기</div>
          </div>
        </div>
      </div>
      <div class="g g-f">
        <div class="f">
          <div class="fitem f-a">MacBook Air</div>
          <div class="fitem f-b">
            <div>막강한 성능의 M2</div>
          </div>
          <div class="fitem f-c">
            <div class="c">더 알아보기</div>
            <div class="c">구입하기</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
  * {
    font-family: 'Nanum Gothic', sans-serif;
    box-sizing: border-box;
  }
  .container {
    margin-top: 44px;
    width: 100%;
    background: #fff;
    .des {
      color: #1D1D1F;
      background: #eee;
      width: 100%;
      font-size: 13px;
      margin: auto;
      font-weight: 600;
      display: flex;
      flex-wrap: wrap;
      .d {
        line-height: 1.5;
        padding: 15px 0;
        /* max 하면서 기본 width도 100%로 해야 max이하로갈때 반응형으로 적용된단 -> max이상으로만 안가고 반응형 느낌 */
        /* 태블릿이난 모바일로 줄어들면서 반응형으로 위치 조정하면서 나머지 자잘한건 내려깎는 느낌 ㄱ */
        max-width: 870px;
        width: 90%;
        text-align: center;
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
      background-image: url('/public/apple_pay(pc).jpg');
      margin-top: 0;
      .f {
        max-width: 480px;
        width: 100%;
        margin: auto;
        text-align: center;
        padding-top: 55px;
        .f-a {
          font-size: 56px;
          font-weight: bold;
        } 
        .f-b {
          margin-top: 20px;
          font-size: 28px;
          font-weight: bold;
          .b {
            margin-top: 10px;
          }
        }
        .f-c {
          display: flex;
          justify-content: center;
          margin-top: 25px;
          font-size: 20px;
          color: #0066CC;
          font-weight: bold;
          .c {
            cursor: pointer;
            &:last-child {
              margin-left: 35px;
            }
          }
        }
        .f-one {
          span {
            cursor: pointer;
          }
        }
      }
    }
    .iphone-ug {
      background-image: url('/public/iphone(pc).jpg');
      .f {
        max-width: 480px;
        width: 100%;
        margin: auto;
        text-align: center;
        padding-top: 55px;
        .f-a {
          font-size: 56px;
          color: #fff;
          font-weight: bold;
        } 
        .f-b {
          color: #fff;
          margin-top: 20px;
          font-size: 23px;
          font-weight: bold;
        }
        .f-c {
          display: flex;
          justify-content: center;
          margin-top: 25px;
          font-size: 20px;
          color: #0066CC;
          font-weight: bold;
          .c {
            cursor: pointer;
            &:last-child {
              margin-left: 35px;
            }
          }
        }
      }
    }
    .watch {
      background-image: url('/public/iphone_many(pc).jpg');
      .f {
        max-width: 480px;
        width: 100%;
        margin: auto;
        text-align: center;
        padding-top: 55px;
        color: #000;
        .f-a {
          font-size: 56px;
          font-weight: bold;
          display: flex;
          justify-content: center;
          align-items: center;
        } 
        .f-b {
          margin-top: 20px;
          font-size: 23px;
          font-weight: bold;
          .b {
            margin-top: 10px;
          }
        }
        .f-c {
          display: flex;
          justify-content: center;
          margin-top: 25px;
          font-size: 20px;
          color: #0066CC;
          font-weight: bold;
          .c {
            cursor: pointer;
            &:last-child {
              margin-left: 35px;
            }
          }
        }
      }
    }
    .gbox {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      grid-gap: 10px;
      margin: 10px;
      .g {
        width: 100%;
        height: 580px;
        /* bacgkround - img */
        background-position: center;
        background-repeat: no-repeat;
        /* size - 100% -> 100%만큼의 크기로 줄어든다, cover 100%크기로 늘어난다 */
        background-size: cover;
        .f {
          max-width: 480px;
          width: 100%;
          margin: auto;
          text-align: center;
          padding-top: 55px;
          .f-a {
            font-size: 40px;
            color: #fff;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
          } 
          .f-b {
            color: #fff;
            margin-top: 20px;
            font-size: 21px;
            font-weight: bold;
          }
          .f-c {
            display: flex;
            justify-content: center;
            margin-top: 25px;
            font-size: 17;
            color: #0066CC;
            font-weight: bold;
            .c {
              cursor: pointer;
              &:last-child {
                margin-left: 35px;
              }
            }
          }
        }
      }
      .g-a {
        position: relative;
        background: #000;
        /* 1 - video */
        .video {
          position: absolute; 
          top: 0; 
          left: 0;
          width: 100%; 
          height:100%; 
        }
        .f {
          position: absolute;
          left: 0;
          right: 0;
          z-index: 100;
          .f-one {
            span {
              cursor: pointer;
            }
          }
        }
      }
      .g-b {
        background-image: url('/public/watch(pc).jpg');
        .f {
          .f-a-a {
            color: red;
            margin-top: 10px;
          }
        }
      }
      .g-c {
        background-image: url('/public/notebook(pc).jpg');
        .f {
          .f-a,
          .f-b {
            color: #000;
          }
        }
      }
      .g-d {
        background-image: url('/public/mac_pro(pc).jpg');
      }
      .g-e {
        background-image: url('/public/airpods(pc).jpg');
      }
      .g-f {
        background-image: url('/public/mac_air(pc).png');
        .f {
          .f-a,
          .f-b {
            color: #000;
          }
        }
      }
    }
  }

  /* tablet 사진 */
  @media screen and (max-width: 1070px) {
    .container {
      .des {
        .d {
          width: 82.5%;
        }
      }
      .i {
        height: 705px;
      }
      .iphone {
        background-image: url('/public/apple_pay(tablet).jpg');
        .f {
          padding-top: 60px;
          .f-a {
            font-size: 48px;
          }
          .f-b {
            font-size: 24px;
          }
          .f-c {
            font-size: 19px;
          }
        }
      }
      .iphone-ug {
        background-image: url('/public/iphone(tablet).jpg');
        .f {
          padding-top: 60px;
          .f-a {
            font-size: 48px;
          }
          .f-b {
            font-size: 24px;
          }
          .f-c {
            font-size: 19px;
          }
        }
      }
      .watch {
        background-image: url('/public/iphone_many(tablet).jpg');
        .f {
          padding-top: 60px;
          .f-a {
            font-size: 48px;
          }
          .f-b {
            font-size: 24px;
          }
          .f-c {
            font-size: 19px;
          }
        }
      }
      .gbox {
        .g {
          .f {
            .f-a {
              font-size: 32px;
            }
            .f-b {
              font-size: 19px;
            }
          }
        }
        .g-a {

        }
        .g-b {
          background-image: url('/public/watch(tablet).jpg');
        }
        .g-c {
          background-image: url('/public/notebook(tablet).jpg');
        }
        .g-d {
          background-image: url('/public/mac_pro(tablet).jpg');
        }
        .g-e {
          background-image: url('/public/airpods(tablet).jpg');
        }
        .g-f {
          background-image: url('/public/mac_air(tablet).png');
        }
      }
    }
  }
  /* mobile 전환 */
  @media screen and (max-width: 833) {
    .container {
      .des {
        .d {

        }
      }
    }
  }
  /* mobile 사진 */
  @media screen and (max-width: 735px) {
    .container {
      .des {
        .d {
          width: 87.5%;
          max-width: 405px;
        }
      }
      .i {
        height: 505px;
      }
      .iphone {
        background-image: url('/public/apple_pay(mobile).jpg');
        .f {
          .f-a {
            font-size: 32px;
          }
          .f-b {
            font-size: 19px;
          }
          .f-c {
            font-size: 17px;
          }
        }
      }
      .iphone-ug {
        background-image: url('/public/iphone(mobile).jpg');
        .f {
          .f-a {
            font-size: 32px;
          }
          .f-b {
            font-size: 19px;
          }
          .f-c {
            font-size: 17px;
          }
        }
      }
      .watch {
        background-image: url('/public/iphone_many(mobile).jpg');
        .f {
          .f-a {
            font-size: 32px;
          }
          .f-b {
            font-size: 19px;
          }
          .f-c {
            font-size: 17px;
          }
        }
      }
      .gbox {
        display: flex;
        flex-direction: column;
        .g {
          height: 540px;
          .f {
            .f-a {
              font-size: 32px;
            }
            .f-b {
              font-size: 19px;
            }
          }
        }
        .g-a {

        }
        .g-b {
          background-image: url('/public/watch(mobile).jpg');
        }
        .g-c {
          background-image: url('/public/notebook(mobile).jpg');
        }
        .g-d {
          background-image: url('/public/mac_pro(mobile).jpg');
        }
        .g-e {
          background-image: url('/public/airpods(mobile).jpg');
        }
        .g-f {
          background-image: url('/public/mac_air(mobile).png');
        }
      }
    }
  }
</style>