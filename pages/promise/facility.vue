<template>
  <div class="promise">
    <h1 class="title">시설</h1>

    <h2>
      하이브[HY:BE]는 학우 여러분들을 위한 ‘차별화된 시설’을 제공하겠습니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 업소용 원두 커피머신&제빙기 설치
          <br />&nbsp;&nbsp;&nbsp;(100% 사비로 진행)
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
            한양약대 학우들의 커피 및 음료 소비량은 매우 높은 편입니다. 이로
            인해 학우 여러분들의 경제적 부담도 적지 않을 것이고 약학관에서
            카페까지 멀기에 불편을 느끼실 겁니다. 휴게실에서 커피를 제공함으로써
            학우 여러분의 복지 향상에 크게 기여하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            학생회비로 진행하기에는 불가능한 공약입니다. 따라서 100% 사비로
            진행하겠습니다. 이번 선거에서 당선된다면 학우 여러분들께서 2022년
            2학기 기말고사 기간에 바로 커피머신을 이용하실 수 있도록 즉각적인
            준비와 설치를 약속드리겠습니다. 커피 머신은 닥터커피의 F11 PLUS
            모델을 검토 중입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 430L 업소용 냉장고 설치(100% 사비로 진행)
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
            커피 및 음료의 소비량이 많다보니 냉장고 설치에 대한 요구가
            많았습니다. 시험기간에는 약학 도서관을 이용하며 휴게실에서 취식하는
            학우분들이 많고, 이에 따라 음료 및 음식물을 보관하기 위한 냉장시설에
            대한 수요를 만족시키고자 냉장고를 설치하려고 합니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            커피머신&제빙기와 마찬가지로 가격상 학생회비로 구매하기 힘든
            제품입니다. 따라서 100% 사비로 진행하겠습니다. 이번 선거에서
            당선된다면 학우분들께서 2022년 2학기 기말고사 기간에 바로 이용하실
            수 있도록 즉각적인 준비와 설치를 약속드리겠습니다. 냉장고는 스타쿨
            프리탑 FT-470RS 모델을 검토 중입니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          3. 화장실 비데 설치(100% 사비로 진행)
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
            약학대학 시간표 특성상 오랜 시간 약학관 내에서 생활하는 학우분들이
            많습니다. 이에 따라 화장실 이용 횟수가 많은 것에 반해 화장실 위생
            시설은 부족하다는 의견이 많아 비데를 설치하고자 합니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            앞의 시설들과 마찬가지로 확생회비로 진행하기 어려운 공약입니다.
            따라서 100% 사비로 진행하겠습니다. 모든 학년이 수업을 듣는 2층 남녀
            화장실에 비데를 1대씩 설치하겠습니다. 비데는 Cooing의 BCU-100N
            모델을 검토 중입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          4. 여성, 남성 수면실 분리
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
            <h4>필요성</h4>
            현재 여학우들의 수면실 이용률이 현저히 낮습니다. 그 이유로 저희는
            현재 남녀 수면실이 분리되어 있지 않아 학우분들이 이용하기에 불편하기
            때문이라고 판단했습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            현재 수면실에 있는 사물함과 대여사업 물품들을 지하 1층으로 옮겨
            충분한 수면 공간을 확보하여 남, 여 수면실을 분리함으로써 여학우들의
            수면실 이용률을 높이고자 합니다. 이를 통해 수면 환경이 개선되고,
            여학우뿐만 아니라 남학우도 수면실 이용이 편해질 것입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          5. 약도 및 국시실 시설 개선
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
              1. 공기 청정기 : 국시실과 칸막이 열람실의 환기 문제를 해결하기
              위해 공기 청정기를 설치하겠습니다. 공기의 질을 개선하여 쾌적한
              학습 환경을 제공함으로써 집중도 향상을 기대할 수 있습니다.
            </p>
            <p class="listp">
              2. 백색소음기 : 휴게실 소음을 비롯한 각종 소음을 줄이기 위해
              백색소음기를 설치하겠습니다.
            </p>
            <p class="listp">
              3. 가습기 : 겨울철 난방으로 인한 건조한 학습 환경을 개선하고자
              가습기를 설치하겠습니다.
            </p>
            <p class="listp">
              4. 벌레 퇴치기 : 여름철 모기와 여러 벌레로 인해 불편한 경우가
              많은데, 벌레 퇴치기를 설치하여 해결하도록 하겠습니다.
            </p>
            <p class="listp">
              5. 행거 및 옷걸이 : 두꺼운 겨울옷들을 편리하게 보관할 수 있도록
              국시실에 행거와 옷걸이를 설치하겠습니다.
            </p>
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
