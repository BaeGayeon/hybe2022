<template>
  <div id="index">
    <!-- <div><img class="hello" src="../assets/images/hello.jpg" /></div> -->
    <div id="btns">
      <ul>
        <li
          class="btn btn1"
          @click="showPromise"
          :class="{ pushbtn: viewpromise == true }"
        >
          하이브[HY:BE] 주요공약 확인하기
          <img class="indexarrow" src="../assets/images/right_arrow_2.png" />
        </li>
        <ul>
          <nuxt-link to="promise/facility" v-if="viewpromise">
            <li class="promiseBtn">시설</li>
          </nuxt-link>
          <a href="promise/communication" v-if="viewpromise">
            <li class="promiseBtn">소통</li>
          </a>
          <a href="promise/welfare" v-if="viewpromise">
            <li class="promiseBtn">복지</li>
          </a>
          <a href="promise/event" v-if="viewpromise">
            <li class="promiseBtn">행사</li>
          </a>
          <a href="promise/education" v-if="viewpromise">
            <li class="promiseBtn">교육</li>
          </a>
          <a href="promise/all" v-if="viewpromise">
            <li class="promiseBtn">앞으로의 노력</li>
          </a>
        </ul>
        <nuxt-link to="statement">
          <li class="btn">
            출마의 변 확인하기
            <img class="indexarrow" src="../assets/images/right_arrow_2.png" />
          </li>
        </nuxt-link>
        <a href="profile">
          <li class="btn">
            후보자 약력 확인하기
            <img class="indexarrow" src="../assets/images/right_arrow_2.png" />
          </li>
        </a>
      </ul>
      <img class="candidate" src="../assets/images/people/2.jpeg" />
      <img class="bye" src="../assets/images/bye.jpg" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      viewpromise: false,
    };
  },
  methods: {
    showPromise() {
      if (this.viewpromise == false) {
        this.viewpromise = true;
      } else {
        this.viewpromise = false;
      }
    },
  },
};
</script>

<style>
.hello {
  margin-top: 15px;
  width: 100%;
  margin-bottom: 5px;
}

.candidate {
  margin-top: 20px;
  width: 100%;
}

.bye {
  padding: 0;
  margin: 0;
  width: 100%;
}

.indexarrow {
  width: 20px;
  margin: 2px;
}

#btns {
  background-color: rgb(22, 126, 67);
}

#index {
  background-color: rgb(22, 126, 67);
}

a {
  text-decoration: none;
  background-color: rgba(255, 255, 254, 0);
}

.btn {
  list-style: none;
  text-align: center;
  position: relative;
  align-items: center;
  vertical-align: middle;
  display: inline-flex;
  justify-content: center;
  padding: 10px;
  margin: 12px;
  box-shadow: 0px 5px 0px 0px rgba(236, 213, 79, 1);
  border-radius: 18px;
  background-color: rgba(255, 255, 254, 0.96);
  color: rgb(42, 42, 42);
  font-size: 15px;
  font-weight: 600;
  cursor: pointer;
  width: 74%;
}

.promiseBtn {
  position: relative;
  display: inline-flex;
  justify-content: center;
  padding: 12px;
  margin: 10px 5px 10px 5px;
  box-shadow: 0px 5px 0px 0px rgba(236, 213, 79, 1);
  border-radius: 18px;
  background-color: rgba(255, 255, 254, 0.96);
  color: rgb(42, 42, 42);
  font-size: 15px;
  font-weight: 600;
  gap: 20px 4%;
  flex-wrap: wrap;
  cursor: pointer;
  width: 25%;
}

/* .btn:hover {
  margin-top: 15px;
  margin-bottom: 5px;
  box-shadow: 0px 0px 0px 0px #007144;
} */

/* .btn1:hover {
  margin-top: 5px;
} */

.btn1 {
  margin-top: 0;
}

.pushbtn {
  margin-top: 5px;
  margin-bottom: 5px;
  box-shadow: 0px 0px 0px 0px rgba(22, 126, 67, 255);
}

#btns ul {
  padding: 0;
  margin: 0;
  text-align: center;
  align-items: center;
  margin-left: auto;
  background-color: rgba(22, 126, 67, 255);
  margin-right: auto;
}

#index {
  background-color: rgba(22, 126, 67, 255);
}
</style>
