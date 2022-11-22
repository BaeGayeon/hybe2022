<template>
  <div class="promise">
    <h1 class="title">시설</h1>

    <h2>
      하이브[HY:BE]는 학우 여러분들을 위한 ‘차별화된 시설’을 제공하겠습니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 원두 커피머신&제빙기 설치
          <img
            v-if="!show0"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show0"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show0">
          <div>
            <h4>필요성 및 목표</h4>
            학우들의 커피 소비량과 카페까지의 거리를 고려했을 때, 학우들의
            경제적 부담과 카페에 대한 접근성 문제에 대해 고민해 볼 필요가
            있습니다. HY:BE는 휴게실에 원두 커피머신과 제빙기를 설치하여 학우
            여러분들이 ‘원하는’ 복지를 제공하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            2022년 2학기 기말고사 기간부터 커피머신을 이용하실 수 있도록 12월 중
            설치 완료를 약속드립니다. 커피 머신은 닥터커피의 F11 PLUS 모델을
            계획 중입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 430L 업소용 냉장고 설치
          <img
            v-if="!show1"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show1"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show1">
          <div>
            <h4>필요성 및 목표</h4>
            시험기간 휴게실 내 식음료의 소비량이 많다 보니 냉장고 설치에 대한
            학우들의 요구가 많았습니다. HY:BE는 휴게실에 냉장고를 설치하여 학우
            여러분들이 ‘원하는’ 복지를 제공하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            2022년 2학기 기말고사 기간부터 바로 이용하실 수 있도록 12월 중
            설치완료를 약속드립니다. 냉장고는 스타쿨 프리탑 FT-470RS 모델을 계획
            중입니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 화장실 비데 설치
          <img
            v-if="!show2"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show2"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show2">
          <div>
            <h4>필요성 및 목표</h4>
            시간표 특성상 학우들의 약학관 화장실 사용이 잦은 것에 비해 화장실
            위생 시설이 부족하다는 의견이 있었고 ‘비데’에 대한 요청이 가장
            많았습니다. 화장실에 ‘비데’를 설치하여 학우 여러분들이 ‘원하는’
            복지를 제공하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            모든 학년이 수업을 듣는 2층 남, 여 화장실에 비데를 1대씩
            설치하겠습니다. 비데는 Cooling의 BCU-100N 모델을 계획 중입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          4. 약학 도서관/국시실 시설 개선
          <img
            v-if="!show3"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show3"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show3">
          <div>
            <h4>필요성 및 목표</h4>
            <p class="listp">
              1. 공기 청정기 : 칸막이 열람실과 국시실의 환기 문제를 해결하기
              위해 공기청정기를 설치하겠습니다. 공기의 질을 개선함으로써 쾌적한
              학습환경을 제공하겠습니다.
            </p>
            <p class="listp">
              2. 백색소음기 : 휴게실 소음을 비롯한 각종 소음을 줄이기 위해
              백색소음기를 설치하겠습니다.
            </p>
            <p class="listp">
              3. 가습기 : 겨울철 난방으로 인해 건조한 학습 환경을 개선하기 위해
              가습기를 설치하겠습니다.
            </p>
            <p class="listp">
              4. 벌레 퇴치기 : 모기를 비롯한 각종 벌레들로 인해 학습에 방해되는
              경우가 있는데, 벌레 퇴치기를 설치하여 쾌적한 학습 환경을
              제공하겠습니다.
            </p>
            <p class="listp">
              5. 행거 및 옷걸이 : 두꺼운 겨울옷들을 편리하게 보관할 수 있도록
              행거와 옷걸이를 설치하겠습니다.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 수면실 남,여 분리 및 담요 구비
          <img
            v-if="!show4"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show4"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show4">
          <div>
            <h4>필요성</h4>
            지금까지 여학우들의 수면실 이용률은 현저히 낮았습니다. 이는 남,여
            따로 분리되어 있지 않은 현재 수면실의 구조가 원인이라 판단됩니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            현재 수면실에 배치된 사물함 & 대여사업 물품을 지하 1층으로 옮김 +
            수면실 공간을 남, 여로 분리
            <br />
            → 충분한 수면 공간 확보
            <br />
            → 여학우들의 수면실 이용률 상승
            <br />
            → 수면 환경이 개선되어 학우들의 수면실 이용이 편리해짐
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show0: false,
      show1: false,
      show2: false,
      show3: false,
      show4: false,
    };
  },
  methods: {},
};
</script>

<style>
.promise h2 {
  position: relative;
  padding-left: 10px;
  color: rgb(22, 126, 67, 1);
  border-top: 2px solid rgb(22, 126, 67, 1);
  border-bottom: 2px solid rgb(22, 126, 67, 1);
  padding: 10px;
  margin-left: 10px;
  margin-right: 10px;
  font-size: 20px;
  text-align: center;
  font-weight: 600;
  background-color: white;
}

h1.title {
  text-align: center;
  padding: 15px;
  background-color: white;
}

.promise h3 {
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 0;
  margin: 0px 10px 0 10px;
  border-top: 0.5px solid rgb(185, 185, 185);
  border-bottom: 1px solid rgb(185, 185, 185);
  padding: 15px 10px 15px 10px;
  font-size: 14.5px;
  font-weight: 500;
  background-color: white;
}

.atitle0 {
  border-top: none;

  background-color: white;
}

span {
  height: 3px;
  background-color: white;
}

.arrow {
  width: 20px;
  vertical-align: middle;
  float: right;
}

.promise {
  /* background-color: white; */
  padding: 0;
  margin: 0;
}

.acontents {
  margin: 0px 10px 0 10px;
  padding: 20px;
  padding-top: 5px;
  background-color: rgb(235, 235, 235);
}

.acontents * {
  background-color: rgb(235, 235, 235);
  line-height: 25px;
}

.promise h4 {
  padding: 10px 0 10px 5px;
}

.listp {
  padding-bottom: 10px;
}
</style>
