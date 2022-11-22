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
            현재 선후배 간 연결고리 역할을 하는 멘토멘티 문화가 있습니다.
            하지만, 그간 학생회 측에서 멘토멘티 문화 활성화에 실질적인 도움을 줄
            수 있는 부분이 적었던 것이 사실이며, 이로 인해 멘토멘티 문화가
            선후배 간 연결고리라는 소기 목적을 충분히 이루지 못하고 있었습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            기존의 멘토멘티 모임은 유지하되, 4부를 형성하여 현재의 문제점을
            해결하겠습니다. 현재 17개로 이루어진 멘토멘티 조를 4개로 묶어 4개의
            부를 형성하고자 합니다. 학생회 주도로 4부 체육대회, 4부
            농촌봉사활동, 4부 등산여행, 4부 놀이공원 행사와 같은 4부 행사들을
            기획하여 선후배 간 교류를 활성화 시키겠습니다. 더 나아가 멘토 멘티
            간 유대감 형성을 위해 교수님 동반 4부 행사도 고려해보겠습니다.
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
            올해 남부지부 약대생 간 교류 기회는 학생회 인원들에게만 제한적으로
            주어졌습니다. 타 약대생과의 교류기회는 모든 재학생들에게 주어져야
            합니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            남부지부 체육대회에서 타 학교와의 대항전뿐만 아니라 타 약대생과 조를
            이루어 조별 미니게임을 진행하고, 뒷풀이까지 기획하여 남부지부 약대생
            간 만남의 장을 형성하겠습니다. 장소는 ‘과천관문공원’과 컨택이
            되었고, 남부지부 6개 학교 중 4개 학교에서 긍정적인 답변을
            받았습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 새내기 배움터 기획
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
        <h3 class="atitle0" @click="show3 = !show3">
          4. 남부지부 문화생활 소모임 신설
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
            문화생활(독서, 야구관람, 뮤지컬 및 연극 관람, 등산 등) 소모임을
            만들고 싶어도 학과 내 수요가 적은 상황입니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            남부지부 문화생활 소모임을 통해 문화생활을 향유하는 한편, 더 나아가
            현재 부족했던 남부지부 약대생 간 교류를 활성화하겠습니다. 구성된
            소모임이 연합동아리로 발전한다면 남부지부 전체에 긍정적 효과를
            기대할 수 있습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 미리배움터 기획
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
            올해 신입생들은 입학 전 선배들과 만날 수 있는 기회가 없었습니다.
            이로 인해 학교생활에 대한 정보가 부족하여 학기 초반에 적응하기
            어려웠다는 의견이 있었습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            미리배움터를 기획하여 개강 전 신입생과 재학생들 간의 만남의 자리를
            마련하겠습니다. 선배가 신입생에게 학교생활 전반에 대한 정보를
            제공하는 등 자연스러운 선후배 간 교류를 이끌고 신입생의 원만한 학교
            적응을 돕겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show5 = !show5">
          6. 새내기 배움터 (총 엠티) 기획
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
            코로나 이전에는 총 엠티를 비롯한 다양한 학과 행사들을 통하여 선후배
            간 교류가 활발했지만, 그간 오프라인 행사들이 제한되면서 학과
            분위기가 다소 침체된 경향이 있습니다.
          </div>
          <div>
            <h4>목표</h4>
            코로나 세대 이전의 가장 큰 행사였던 총 엠티를 부활시켜 끈끈한 선후배
            관계를 되찾겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show6 = !show6">
          7. 축제기간 약학대학 주점 운영
          <img
            v-if="!show6"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show6"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show6">
          <div>
            <h4>필요성</h4>
            올해 한양약대는 에리카 축제기간 동안 주점과 부스를 운영하지
            않았습니다. 학과 주점과 부스가 없어서 타 학과와의 교류 부족과 에리카
            내 약학과 홍보 부족에 대해 아쉬웠다는 의견이 있습니다. 이와 더불어
            축제기간 다른 학과 주점을 이용해야 하는 상황으로 인해 학과에 대한
            소속감을 느끼지 못했다는 의견도 있습니다.
          </div>
          <div>
            <h4>목표</h4>
            축제 기간 약대 주점 및 부스 운영은 타 학과와의 자연스러운 교류, 본교
            내 약학과 홍보의 기회가 될 것입니다. 또한 주점기획단을 통해 비학생회
            학우들에게 학생회 활동 기회를 제공하여 학우들이 학과 행사에
            능동적으로 참여하게 되는 계기가 될 것입니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show7 = !show7">
          8. 남부지부 행사 다양화
          <img
            v-if="!show7"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show7"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show7">
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
      show5: false,
      show6: false,
      show7: false,
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
