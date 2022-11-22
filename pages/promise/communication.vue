<template>
  <div class="promise">
    <h1 class="title">소통</h1>

    <h2>
      하이브[HY:BE]는 투명한 공개와 수용을 통해 ‘장벽 없는 소통’을 약속합니다.
    </h2>
    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show0 = !show0">
          1. 공약 이행 타임라인 제작
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
            후보자는 실현 가능한 공약만을 제시해야 하며, 학우들은 후보자의
            공약들이 잘 이행되고 있는 지 알 수 있어야 합니다. 또한 학생회 사업의
            진행과정이 잘 알려지지 않아 궁금하다는 의견이 많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            매 분기별 공약 이행 타임라인을 제작하여 오프라인 또는 온라인으로
            게시하겠습니다. 이를 통해 공약들이 실제로 잘 지켜지고 있는지와
            더불어 학생회 사업 진행과정을 투명하게 공개하여 학우들의 알 권리를
            보장하겠습니다.
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
            학우들이 학생회비 명목으로 납부한 25만원이라는 큰 금액이 어디에
            사용되었는지 어떻게 관리되고 있는지 누구나 알 수 있어야 합니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            학생회비 공개감사를 진행하여 학생회비 사용처와 사용된 금액을
            투명하게 공개하여 학우들의 알 권리를 보장하겠습니다. 동시에 학생회비
            현황과 사용 계획에 대해 공지하여 효율적이고 청렴하게 학생회비를
            관리하겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show2 = !show2">
          3. 불편소리함 카카오톡 익명 오픈채팅방 개설
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
            현재 학생회에서 진행하는 업무나 행사에 대해 궁금해하시거나 피드백을
            하고 싶어도 쉽게 다가가기 어려웠다는 학우분들이 많았습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            카카오톡 1:1 익명 오픈 채팅방을 개설하여 학우분들이 학년과 나이
            상관없이 편리하게 문의할 수 있도록 하겠습니다.
            <br />
            → 학우들과 학생회 간 소통의 진입장벽 ↓
            <br />
            → 빠른 피드백을 통해 학우분들의 요구 신속하게 반영
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show3 = !show3">
          4. 소통 학생 위원회 구성
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
            학생회가 무인매점 사업, 제휴 사업, 협찬 사업에 대해 학우들의 의견을
            반영하기보다 결과 공지만을 해오며 일방적인 소통을 해왔다고
            생각합니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            학생회가 무인매점 사업, 제휴 사업, 협찬 사업에 대해 학우들의 소중한
            의견을 적극 반영하겠습니다. 익명 구글폼을 활용해 익명성을
            보장함으로써 학생회와 학우 간 소통의 질을 높이겠습니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show4 = !show4">
          5. 졸업생과의 네트워크 형성
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
            현재 졸업생 단톡방을 통해 공유되는 학술 정보, 취업 정보, 약국
            파트타임 정보에 대한 재학생들의 접근은 제한적입니다. 또한 한양약대는
            신설 약대로 동문회가 아직 활성화되지 않아 재학생과 졸업생 간 교류
            기회가 거의 없는 상황입니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            학양약대 1기~ 내년 입학 예정인 13기와 15기까지 전체 기수 카톡방을
            개설하여 졸업생 선배님들끼리 공유되었던 유용한 정보를 재학생들에게도
            제공하겠습니다. 또한 졸업생과 재학생 간 네트워크 형성을 통해 정보
            공유뿐만 아니라 OB YB 체육대회, 동문 선배 초청 강연, 홈 커밍데이와
            같은 행사를 활성화하여 한양약대에 대한 자부심과 애교심을 높이고자
            합니다.
          </div>
        </div>
      </div>
    </div>

    <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show5 = !show5">
          6. 한양약대 SNS/유튜브 활성화
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
            지금까지 한양약대는 카카오톡과 인스타그램이라는 제한된 매체를 통해
            학과의 소식들을 전달해왔습니다. 유튜브와 에브리타임 등의 추가적인
            플랫폼을 통해 정보 제공 경로를 다양화함으로써 학우들의 알 권리를
            보장하겠습니다.
          </div>
          <div>
            <h4>계획 및 목표</h4>
            <ul></ul>
            <div>
              <li class="list1">인스타그램 활성화</li>
              <ul>
                <li class="list2">
                  업로드 빈도를 높여 학우들에게 학과 행사와 소식들을 빠르게
                  공유하겠습니다.
                </li>
                <li class="list2">
                  학우들이 다같이 참여할 수 있는 스토리 태그 행사를
                  진행하겠습니다.
                  <br />(벚꽃행사, 등산여행 인증, 밥약 인증 등)
                </li>
                <li class="list2">
                  한양약대 특색에 맞는 인스타 스토리 필터를 제작하여 학우들이
                  일상적인 스토리를 업로드할 때 사용할 수 있도록 하겠습니다.
                </li>
              </ul>
            </div>
            <br />
            <div>
              <li class="list1">한양대학교 약학대학 유튜브 활성화</li>
              <ul>
                <li class="list2">
                  학생회와 비학생회 학우들로 이루어진 ‘한양약대 서포터즈’를
                  구성하여 다양한 콘텐츠의 영상을 제작하고 유익한 정보를
                  전달하겠습니다. ‘한양약대 서포터즈’는 비학생회 학우들에게도
                  학생회 활동 기회를 주어 능동적 참여를 유도하겠습니다.
                </li>
              </ul>
            </div>
            <br />
            <div>
              <li class="list1">에브리타임 약대 게시판 개설</li>
              <ul>
                <li class="list2">
                  에브리타임 한양약대 게시판을 개설하여 학과 소식들에 대한
                  접근성을 강화하겠습니다. 학과 행사들에 대한 정보뿐만 아니라
                  학생회 회의 결과까지 공개하여 학우들의 알 권리를
                  보장하겠습니다.
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show6 = !show6">
          6-(1) 인스타그램 활성화
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
          <div class="noh3">
            >업로드 빈도를 높여 학우분들에게 학과 행사와 여러 소식들을 빠르게
            공유하겠습니다. 또한 학우분들의 참여할 수 있는 다양한 스토리 태그
            행사를 진행하겠습니다. (벚꽃축제 인증, 단풍 여행 인증, 시험공부 인증
            ,멘토멘티 밥약 인증 등)
            <br />
            <br />
            >한양약대 특색을 곁들인 인스타 스토리 필터를 제작하여 학우분들이
            일상적인 스토리를 업로드할 때 재미나게 사용할 수 있도록 하겠습니다.
          </div>
        </div>
      </div>
    </div> -->

    <!-- <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show7 = !show7">
          6-(2) 한양대학교 약학대학 유튜브 제작
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
          <div class="noh3">
            한양약대 서포터즈’를 구성하여 다양한 영상 콘텐츠를 제작하고 교내 타
            단체 유튜브 채널과 친구채널을 맺어 유익한 정보를 전달함으로써
            한양약대를 홍보함과 동시에 정보전달의 장을 넓히겠습니다. ‘한양약대
            서포터즈’에는 학생회 인원뿐만 아니라 비학생회 학우분들도 같이 참여할
            수 있도록 하겠습니다.
          </div>
        </div>
      </div>
    </div> -->

    <!-- <div class="atitle">
      <div>
        <h3 class="atitle0" @click="show8 = !show8">
          6-(3) 에브리타임 약대 게시판 개설
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
          <div class="noh3">
            에브리타임에 한양약대 게시판을 개설하여 교내의 정보들에 대한
            접근성을 높이겠습니다. 행사 정보공유, 학생회 회의록 및 자료 공유,
            문의사항 수용 등을 통해 학우분들께서 편하게 소통하고 유익한 정보를
            받을 수 있는 공간을 만들겠습니다.
          </div>
        </div>
      </div>
    </div> -->
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
      // show6: false,
      // show7: false,
      // show8: false,
    };
  },
  methods: {},
};
</script>

<style>
.list1 {
  padding-left: 5px;
}

.list2 {
  padding-left: 5px;
}
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
  /* width: 0px; */
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

.noh3 {
  padding-top: 13px;
}
</style>
