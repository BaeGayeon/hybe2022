<template>
  <div class="promise">
    <h1 class="title">교육</h1>

    <h2>
      하이브[HY:BE]는 학우 여러분들을 위한 ‘진로탐색의 교육’을 주도하겠습니다.
    </h2>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 팜터뷰 & 동문 선배님들의 초청 강연 주최
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
            <h4>필요성</h4>
            약국, 병원. 제약 회사 등 약사로서 진출할 수 있는 분야에 대해 정보를
            얻고 싶지만, 세미나 및 강연이 교외에서 진행되어 들으러 가기 쉽지
            않다는 의견이 많았습니다. 이에 학생회가 주도하는 진로 탐색
            프로그램이 있어야 한다고 생각했습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            한양약대 교수님들께 인터뷰를 요청하여 ‘팜터뷰’를 진행함으로써
            학우들께 다양한 진로에 대한 양질의 정보를 제공하겠습니다. 약국,
            병원, 제약회사뿐만 아니라 공직약사와 사회약사 등 다양한 직군에
            종사하고 계시는 동문 선배님들의 초청 강연을 주최하겠습니다. 팜터뷰와
            동문 선배님 초청 강연 모두 교내에서 진행하고 인터뷰와 강연 내용들을
            한양약대 SNS에 게시해 진로탐색 기회의 접근성을 높이겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 방학기간 중 연구실 및 회사 인턴 활성화
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
            <h4>필요성</h4>
            방학기간 중 약대생 개인으로서 진로를 탐색할 수 있는 기회가
            부족하다는 의견이 많아 학생회 차원에서의 진취적인 지원이 필요합니다.
          </div>
          <div>
            <h4>계획</h4>
            방학기간은 상대적으로 시간적 여유가 많아 자기 계발 시간으로 활용하기
            좋습니다. 인턴 채용정보를 공유함으로써 직접적이고 능동적인 진로
            탐색의 기회를 제공하겠습니다.
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
