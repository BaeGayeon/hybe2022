<template>
  <div class="promise">
    <h1 class="title">복지</h1>

    <h2>
      하이브[HY:BE]는 학우 여러분들께 <br />‘격이 다른 복지’을 제공하겠습니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 무인매점 메뉴 및 운영기간 확대&가격인하
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
            이번 학기에 진행된 무인매점 사업에 대한 학우들의 반응이 매우
            긍정적입니다. 이를 발전시키기 위해 무인매점 메뉴 다양화, 운영시간
            확대, 가격 인하의 방향성을 가지고 사업을 진행하겠습니다.
          </div>
          <div>
            <h4>계획</h4>
            설문조사를 통해 메뉴 선정에 있어 학우들의 의견을 적극
            반영하겠습니다. 방학을 제외한 학기 내내로 운영시간을 확대하고, 대량
            구매를 통해 구매단가를 낮추어 가격을 인하하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 대여사업 품목 확대
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
            현재 진행하고 있는 대여사업을 이어서, 학우분들께서 더 많은 물품을
            사용할 수 있도록 하겠습니다.
            <h4>계획</h4>
            독서대, 담요, 보조배터리, 충전기, 배드민턴 채를 추가로 구비하여
            대여사업 품목을 확대하겠습니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          3. 제휴사업 확대 및 혜택 강화
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
            현재 한양약대 제휴업체는 음식점과 술집 위주로 학우들이 충분한 혜택을
            누리지 못하고 있습니다. 카페, 노래방, 병원, 약국, 헬스장, 스터디카페
            등 학우분들이 자주 가는 업체 위주로의 제휴업체 다양화와 혜택 강화를
            통해 풍부한 제휴 혜택을 누릴 수 있도록 하겠습니다.
          </div>
          <div>
            <h4>계획</h4>
            설문조사를 통해 학우분들이 원하는 제휴업체들을 선정한 후, 다양한
            제휴업체와 학우들에게 충분한 혜택이 될 수 있는 조건으로 계약할
            것입니다. 계약 체결을 완료한 제휴 업체는 공식 인스타그램과 공지방을
            통해 공유하고 가게 앞에 포스터를 부착하여 학우들에게 홍보하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          4. 동아리 승격 절차 및 요건 완화 추진

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
            현재 소모임이 정식 동아리로 등록되기 위해서는 오랜 시간을 걸쳐 2번의
            승격심사를 거치는 등 많은 시간과 노력이 필요합니다. 이 과정을
            완하하고자 합니다.
          </div>
          <div>
            <h4>목표</h4>
            정식 동아리로 등록되어야 행정실의 지원을 받을 수 있기 때문에, 활발한
            활동을 하고 있는 소모임이 지원받지 못한다는 아쉬움을 해소하고자
            합니다. 또한 절차 및 요건 완화를 통해 신규 소모임 활동을 장려하는
            효과도 기대할 수 있습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          5. 동아리 지원금을 통한 동아리방 환경 개선
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
            <h4>필요성</h4>
            현재 지하 1층 동아리방은 공연 동아리를 제외하면 창고로 쓰이거나
            관리가 제대로 되지 않고 있어 시설이 훼손되어 있는 부분이 있습니다.
            또한 지하 1층에 벌레가 많이 나와 불쾌함을 느낀다는 의견이
            많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            동아리 지원금을 통해 지하 1층 동아리방 환경을 개선하고, 훼손된
            시설을 복구하여 동아리나 소모임 활동 시간 외 재학생들의 사용에도
            불편이 없도록 하겠습니다. 또한 지하 1층에 벌레퇴치제 및 벌레퇴치기를
            구비하여 보다 쾌적한 환경을 만들겠습니다.  
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
  padding: 15px;
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
</style>
