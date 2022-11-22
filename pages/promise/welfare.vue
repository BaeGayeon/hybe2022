<template>
  <div class="promise">
    <h1 class="title">복지</h1>

    <h2>
      하이브[HY:BE]는 학우 여러분들께 <br />‘격이 다른 복지’을 제공하겠습니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 무인매점 메뉴 다양화, 운영기간 확대 및 가격 인하
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
            이번 학기 진행된 무인매점 사업에 대한 학우들의 평가가 매우
            긍정적입니다. 지속적으로 발전되는 사업을 목표로 무인매점 메뉴
            다양화, 운영기간 확대, 가격 인하라는 3가지 방향성을 갖고 사업을
            진행하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            설문조사를 통해 메뉴 선정에 있어 학우들의 의견을 적극
            반영하겠습니다. 무인매점을 학기 중 상시 운영하는 한편, 도소매 구매를
            통해 구매 단가를 낮추어 가격을 인하하겠습니다.
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
            <h4>도입 계획</h4>
            독서대, 담요, 보조배터리, 충전기, 배드민턴 채를 추가 구비하여
            대여사업 품목을 다양화하겠습니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 제휴업체 확대 및 혜택 강화
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
            현재 한양약대 제휴 업체들은 음식점과 술집 위주로 학우들의 혜택이
            요식업계에 제한되어 있습니다. 카페, 노래방, 병원, 약국, 헬스장,
            스터디카페 등 학우들이 자주 이용하여 혜택 받기 좋은 업종 위주로 제휴
            업체를 다양화하는 한편, 제휴 혜택 또한 강화하겠습니다.
          </div>
          <div>
            <h4>도입 계획</h4>
            제휴 업체 다양화와 혜택 강화를 위해 설문조사를 진행하여 학우들의
            수요를 파악하겠습니다. 인스타그램, 카톡 공지방 그리고 오프라인
            포스터를 이용하여 학우들에게 제휴 업체와 혜택에 대해 충분히
            홍보하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          4. 동아리 승격 절차 및 요건 완화 추진
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
            현재 소모임이 정식 동아리로 등록되기 위해서는 오랜 시간을 거쳐 2번의
            승격심사를 통과해야 합니다. 동아리로 승격되어야 행정실의 지원을 받을
            수 있어, 소모임 활동이 활발해도 지원을 받지 못하는 문제가 있습니다.
          </div>
          <div>
            <h4>목표</h4>
            동아리 승격 절차 및 요건 완화를 통해 신규 소모임 활동을
            장려하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 지원금을 통한 동아리방 환경 개선
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
            현재 창고로만 쓰이거나 훼손된 시설이 그대로 방치되어 있는 동아리방이
            있습니다. 또한 여름철에 벌레가 많아 불편을 호소하는 학우들이
            많습니다.
          </div>
          <div>
            <h4>목표</h4>
            시설 복구를 통해 동아리방 환경을 개선하여 학우들의 사용에 불편이
            없도록 하겠습니다. 또한 벌레퇴치기 및 벌레퇴치제를 구비하여 쾌적한
            환경을 만들겠습니다.
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
