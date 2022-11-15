<template>
  <div class="promise">
    <h1 class="title">소통</h1>

    <h2>
      하이브[HY:BE]는 투명한 공개와 수용을 통해 ‘장벽 없는 소통’을 약속합니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 공약 타임라인 제작
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
            후보자는 실현 가능한 공약만을 약속해야 하며, 학우분들은 내가 선택한
            학생회가 실제로 공약을 잘 이행하고 있는지 알 수 있어야 합니다. 또한
            현재 학생회가 하는 일과 진행과정이 잘 알려지지 않아 궁금하다는
            의견이 많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            매 분기별 공약 이행률 타임라인을 제작하여 오프라인 또는 온라인으로
            게시하겠습니다. 이를 통해 학우분들께 약속드린 공약이 실제로 잘
            이루어지고 있는지와 더불어 학생회가 하는 일과 진행과정을 투명하게
            밝혀 학우분들의 알 권리를 보장하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show1 = !show1">
          2. 학생회비 공개감사 진행
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
            한양약대 학우분들은 입학할 때 4년치 혹은 6년치의 학생회비를
            내셨습니다. 그 비용이 어디에 어떻게 사용되고 관리되고 있는지는
            모두에게 공개되어 누구나 알 수 있어야 합니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            학생회비 공개감사를 진행하여 학생회비가 어떻게 사용되었는지 투명하게
            공개하여 학우분들의 알 권리를 보장하겠습니다. 동시에 학생회비 현황과
            사용계획에 대해서 공지하여 효율적이고 청렴하게 학생회비를
            관리하겠습니다.
          </div>
        </div>
      </div>
    </div>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 불편소리함 카카오톡 채팅방 개설
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
            현재 한양약대 제휴업체는 음식점과 술집 위주로 학우들이 충분한 혜택을
            누리지 못하고 있습니다. 카페, 노래방, 병원, 약국, 헬스장, 스터디카페
            등 학우분들이 자주 가는 업체 위주로의 제휴업체 다양화와 혜택 강화를
            통해 풍부한 제휴 혜택을 누릴 수 있도록 하겠습니다.현재 학생회에서
            진행하는 업무나 행사에 대해 궁금해하시거나 피드백을 하고 싶어도 쉽게
            다가가기 어려웠다는 학우분들이 많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            카카오톡 1:1 익명 오픈 채팅방을 개설하여 학우분들이 학년과 나이
            상관없이 편리하게 문의할 수 있도록 하여 학우들과 학생회 간 소통의
            진입장벽을 낮추겠습니다. 또한 빠른 피드백을 통해 학우분들의 요구를
            신속히 반영하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          4. 소통학생위원회 구성
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
            무인매점 사업, 제휴 사업, 협찬 사업 등에 있어서 학생회가 일방적인
            공지만을 하여 학교의 주인인 학우 여러분의 의견을 잘 수렴하지
            못했습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            소통학생위원회를 구성하여, 학생회에서 추진하는 행사나 복지사업에
            대한 학우 여러분의 귀중한 의견을 적극 반영하겠습니다. 의견 취합
            방식은 익명 구글 폼으로 진행하여 익명성을 보장함으로써 학생회와 학우
            간의 소통의 질을 향상하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 재학생과 졸업생 간 교류 형성
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
            현재 지하 1층 동아리방은 공연 동아리를 제외하면 창고로 쓰이거나
            관리가 제대로 되지 않고 있어 시설이 훼손되어 있는 부분이 있습니다.
            또한 지하 1층에 벌레가 많이 나와 불쾌함을 느낀다는 의견이
            많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            한양약대 1기부터 내년 입학할 예정인 13기와 15기까지 전기수 카톡방을
            만들어 현재 졸업생만 접근 가능했던 유용한 정보를 재학생분들도 만나볼
            수 있도록 하겠습니다. 또한 이런 활동을 통해 형성된 네트워크를 통해
            재학생과 졸업생 간 다양한 소모임, OB YB 체육대회, 동문 선배 초청강연
            등 많은 교류를 활성화함으로써 한양약대에 대한 자부심과 애교심을
            높이고자 합니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show5 = !show5">
          6. 한양약대 SNS 활성화
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
            아직 한양약대 SNS가 많이 활성화되지 않았고, 주로 인스타그램을 통해
            한정적으로 이루어지고 있어서 플랫폼이 부족하다는 의견이 많았습니다.
            SNS 활성화를 통해 정보를 빠르게 공유하고 학우분들이 학과 행사나
            소식에 더 많은 관심을 가질 수 있어야 합니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show6 = !show6">
          7. 인스타그램 활성화
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
            >업로드 빈도를 높여 학우분들에게 학과 행사와 여러 소식들을 빠르게
            공유하겠습니다. 또한 학우분들의 참여할 수 있는 다양한 스토리 태그
            행사를 진행하겠습니다. (벚꽃축제 인증, 단풍 여행 인증, 시험공부 인증
            ,멘토멘티 밥약 인증 등) >한양약대 특색을 곁들인 인스타 스토리 필터를
            제작하여 학우분들이 일상적인 스토리를 업로드할 때 재미나게 사용할 수
            있도록 하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show7 = !show7">
          8. 한양대학교 약학대학 유튜브 제작
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
            한양약대 서포터즈’를 구성하여 다양한 영상 콘텐츠를 제작하고 교내 타
            단체 유튜브 채널과 친구채널을 맺어 유익한 정보를 전달함으로써
            한양약대를 홍보함과 동시에 정보전달의 장을 넓히겠습니다. ‘한양약대
            서포터즈’에는 학생회 인원뿐만 아니라 비학생회 학우분들도 같이 참여할
            수 있도록 하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show8 = !show8">
          9. 에브리타임 약대 게시판 개설
          <img
            v-if="!show8"
            class="arrow"
            src="../../assets/images/down-arrow.png"
          />
          <img
            v-if="show8"
            class="arrow"
            src="../../assets/images/up-arrow.png"
          />
        </h3>
        <div class="acontents" v-if="show8">
          <div>
            에브리타임에 한양약대 게시판을 개설하여 교내의 정보들에 대한
            접근성을 높이겠습니다. 행사 정보공유, 학생회 회의록 및 자료 공유,
            문의사항 수용 등을 통해 학우분들께서 편하게 소통하고 유익한 정보를
            받을 수 있는 공간을 만들겠습니다.
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
      show8: false,
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
