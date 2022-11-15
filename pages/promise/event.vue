<template>
  <div class="promise">
    <h1 class="title">행사</h1>

    <h2>
      하이브[HY:BE]는 ‘다채로운 행사’를 기획하여 학우 여러분들의 즐거움을
      책임지겠습니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 4부 형성 (멘토멘티 활용)
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
            현재 선후배 간 연결고리로서 멘토멘티 모임이 있습니다. 하지만
            현실적으로 학생회가 기존의 멘토멘티 모임의 활성화에 도움을 줄 수
            있는 부분이 많이 없었습니다. 또한 지금보다 많은 선배 혹은 후배와
            활발히 교류하고 싶어하는 학우분들이 많았습니다. 이러한 상황에서
            기존의 멘토멘티 모임을 유지하되 4부를 형성하여 현재의 문제점을
            해결할 수 있습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            현재 선후배 간 연결고리로서 멘토멘티 모임이 있습니다. 하지만
            현실적으로 학생회가 기존의 멘토멘티 모임의 활성화에 도움을 줄 수
            있는 부분이 많이 없었습니다. 또한 지금보다 많은 선배 혹은 후배와
            활발히 교류하고 싶어하는 학우분들이 많았습니다. 이러한 상황에서
            기존의 멘토멘티 모임을 유지하되 4부를 형성하여 현재의 문제점을
            해결할 수 있습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 남부지부 체육대회 개최
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
            올해 남부지부 약대생 간 교류가 학생회에 국한되어 있다 보니, 학생회가
            아닌 학우분들도 남부지부 약대생들과 교류가 필요하다는 의견이
            많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            남부지부 체육대회를 추진하여 타 약대생과의 교류의 기회를
            마련하겠습니다. 현재 ’과천관문체육공원‘과 컨택이 되었고 남부지부
            차기 회장단들 (단일후보) 중 4개 학교에서 긍정적 답변을 주신
            상태입니다. 또한 남부지부 행사인 만큼 다른 학교와의 대항전뿐만
            아니라 타 약대생들과 조를 형성하여 미니게임들을 진행하고, 체육대회
            후 뒷풀이를 통해 남부지부 약대생 간의 교류문화를 활성화하겠습니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 남부지부 문화생활 소모임 구성
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
            문화생활(등산, 독서, 야구관람, 뮤지컬 및 연극 관람 등)를 좋아하는
            학우분들께서 우리 학교 내에서는 힘께 같이 즐기는 인원이 적어서
            아쉽고 여럿과 즐기고 싶다는 의견을 주셨습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            같은 문화생활을 즐기는 인원을 남부지부로 확대해 모집하여 소모임을
            구성할 수 있도록 함으로써 문화 생활을 더욱 잘 즐길 수 있음과 동시에
            현재 부족했던 남부지부 교류를 활성화하겠습니다. 이러한 소모임이
            연합동아리로 발전한다면 남부지부 전체에 긍정적 효과를 기대할 수
            있습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          4. 미리배움터 기획
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
            현재 신입생들은 입학하기 전에 선배님들과의 만남 기회가 없었습니다.
            이로 인해 학교생활에 대한 정보나 선배님들과의 교류가 부족하여 학교에
            적응하기가 어려웠다는 의견이 많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            미리배움터를 기획하여 신입생들과 재학생들이 개강 전에 미리 볼 수
            있는 자리를 마련하겠습니다. 선배가 신입생에게 학교생활 전반에 대한
            정보를 제공하는 등 자연스러운 선후배 간 교류를 이끌고 신입생의
            원활한 학교 적응을 도울 수 있습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 새내기 배움터 (총 엠티) 기획
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
            코로나 이전에는 총 엠티 등 많은 학교 행사를 통해 선후배 간의 관계가
            돈독했던 반면, 현재는 많은 행사가 제한되며 조금은 멀어지게
            되었습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            코로나 세대 이전에 하던 행사인 새내기 배움터 (총 엠티)를 다시
            기획함으로써 이전의 끈끈한 선후배 관계를 되찾고 학년 대화합의 장을
            열고자 합니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show5 = !show5">
          6. 축제기간 주점 운영
          <img
            v-if="!show5"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show5"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show5">
          <div>
            <h4>필요성</h4>
            이번년도 에리카 축제에는 약학대학에서 주점을 진행하지 않았습니다.
            축제기간 동안 약학대학 소속으로 준비한 부스나 주점이 없다 보니 약대
            소속감을 느끼지 못해 아쉬웠다는 의견이 많았습니다. 또한 축제기간에
            부스나 주점을 운영하지 않아 에리카 내부에서 약학 대학 홍보나
            타과와의 교류가 부족했다는 의견도 많았습니다.
          </div>
          <div>
            <h4>목표</h4>
            주점 운영을 통해 약대의 소속감과 동시에 타과에 약학대학 홍보 및
            타과와의 자연스러운 교류 기회가 될 것입니다. 또한 축제기간 주점 운영
            준비과정에 주점기획단을 구성하여 비학생회 학우분들도 학교 행사에
            능동적으로 참여할 수 있는 기회를 만들겠습니다.
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
