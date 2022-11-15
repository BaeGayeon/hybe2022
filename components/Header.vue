<template>
  <div id="header">
    <nav class="nav">
      <div class="logo">
        <a href="#" class="logo">
          <img src="../assets/images/logo.png" id="logo-img" />
        </a>
        <div id="text-logo">
          <span style="color: rgb(100, 100, 100)"> 한양약대 선거운동본부 </span>
          <br />
          <span style="color: rgb(50, 50, 50)"> 기호1번 하이브[HY:BE] </span>
        </div>
      </div>
      <input type="checkbox" id="menuicon" />
      <label for="menuicon">
        <span></span>
        <span></span>
        <span></span>
      </label>
      <div class="sidebar">
        <ul>
          <li class="menu menu1">
            <input type="checkbox" id="promisemenu" v-model="promiseview" />
            <img
              class="sidemenuicon"
              src="../assets/images/plus.png"
              v-if="!promiseview"
            />
            <img
              class="sidemenuicon"
              src="../assets/images/minus.png"
              v-if="promiseview"
            />
            <label for="promisemenu">공약</label>
            <ul>
              <a href="pages/promise/facility">
                <li class="menu submenu submenu1" v-if="promiseview">
                  <img
                    class="sidemenuicon"
                    src="../assets/images/minus.png"
                    v-if="promiseview"
                  />
                  시설
                </li>
              </a>
              <li class="menu submenu" v-if="promiseview">
                <img
                  class="sidemenuicon"
                  src="../assets/images/minus.png"
                  v-if="promiseview"
                />
                <a href="pages/promise/communication">소통</a>
              </li>
              <li class="menu submenu" v-if="promiseview">
                <img
                  class="sidemenuicon"
                  src="../assets/images/minus.png"
                  v-if="promiseview"
                />
                <a href="pages/promise/welfare">복지</a>
              </li>
              <li class="menu submenu" v-if="promiseview">
                <img
                  class="sidemenuicon"
                  src="../assets/images/minus.png"
                  v-if="promiseview"
                />
                <a href="pages/promise/event">행사</a>
              </li>
              <li class="menu submenu" v-if="promiseview">
                <img
                  class="sidemenuicon"
                  src="../assets/images/minus.png"
                  v-if="promiseview"
                />
                <a href="pages/promise/education">교육</a>
              </li>
              <li class="menu submenu submenue" v-if="promiseview">
                <img
                  class="sidemenuicon"
                  src="../assets/images/minus.png"
                  v-if="promiseview"
                />
                <a href="pages/promise/all">부록(공약집)</a>
              </li>
            </ul>
          </li>
          <li class="menu">
            <img class="sidemenuicon" src="../assets/images/plus.png" />
            <a href="./statement">출마의 변</a>
          </li>
          <li class="menu">
            <img class="sidemenuicon" src="../assets/images/plus.png" />
            <a href="./profile">후보자 약력</a>
          </li>
          <li class="menu">
            <input type="checkbox" id="snsmenu" v-model="snsview" />
            <img
              class="sidemenuicon"
              src="../assets/images/plus.png"
              v-if="!snsview"
            />
            <img
              class="sidemenuicon"
              src="../assets/images/minus.png"
              v-if="snsview"
            />
            <label for="snsmenu">하이브의 더 많은 이야기</label>
            <ul>
              <a href="https://www.instagram.com/hyup_hy.be_2022">
                <li class="menu submenu submenu1" v-if="snsview">
                  <img
                    class="sidemenuicon"
                    src="../assets/images/minus.png"
                    v-if="snsview"
                  />
                  하이브 인스타그램
                </li>
              </a>
              <a
                href="https://www.youtube.com/channel/UC1g63Zw8O8ks6GuLl7mimww"
              >
                <li class="menu submenu submenue" v-if="snsview">
                  <img
                    class="sidemenuicon"
                    src="../assets/images/minus.png"
                    v-if="snsview"
                  />
                  하이브 유튜브
                </li>
              </a>
            </ul>
          </li>
        </ul>
      </div>
    </nav>
    <div class="imgbg">
      <img class="hello" src="../assets/images/hello.jpg" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      promiseview: false,
      snsview: false,
    };
  },
};
</script>

<style scoped>
#text-logo {
  font-size: 14.4px;
  font-weight: 700;
  /* color: rgb(60, 60, 60); */
}
.hello {
  padding-top: 11px;
  width: 100%;
  padding-bottom: 15px;
  margin: 0;
  background-color: rgb(22, 126, 67);
}

#header ul {
  padding: 0px;
}
nav {
  box-shadow: rgb(100 100 111 / 20%) 0px 7px 29px 0px;
  background-color: #fff;
  display: flex;
  align-items: center;
  height: 78px;
  width: divice-width;
}
.logo {
  box-sizing: content-box;
  flex: 1 0 auto;
  width: 100px;
  display: flex;
  align-items: center;
  background-color: transparent;
}

a {
  color: var(--theme-link-color);
  text-decoration: none;
  cursor: pointer;
}
.menu {
  list-style: none;
  position: relative;
  padding: 10px;
  outline: none;
  font-weight: 500;
  font-size: 18px;
  text-align: left;
  cursor: pointer;
  user-select: none;
  margin: 2px;
  letter-spacing: -1px;
  word-spacing: -2px;
  text-indent: 30px;
}

.menu1 {
  margin-top: 100px;
}

.submenu1 {
  margin-top: 12px;
}

.submenue {
  padding-bottom: 0;
}

#header {
  background-color: rgb(22, 126, 67);
}

.imgbg {
  background-color: rgb(22, 126, 67);
}

#logo-img {
  width: 140px;
  padding-left: 10px;
  padding-top: 5px;
  padding-bottom: 8px;
}

#promisemenu {
  display: none;
}

#snsmenu {
  display: none;
}

.sidemenuicon {
  width: 12px;
  margin-right: 7px;
}

input[id="menuicon"] {
  display: none;
}
input[id="menuicon"] + label {
  display: block;
  margin: 25px;
  margin-left: 20px;
  width: 35px;
  height: 25px;
  position: relative;
  cursor: pointer;
}
input[id="menuicon"] + label span {
  display: block;
  position: absolute;
  width: 100%;
  height: 3px;
  border-radius: 30px;
  background: #000;

  transition: all 0.35s;
}
input[id="menuicon"] + label span:nth-child(1) {
  top: 0;
}
input[id="menuicon"] + label span:nth-child(2) {
  top: 50%;
  transform: translateY(-50%);
}
input[id="menuicon"] + label span:nth-child(3) {
  bottom: 0;
}
input[id="menuicon"]:checked + label {
  z-index: 2;
}
input[id="menuicon"]:checked + label span {
  background: rgb(0, 0, 0);
}
input[id="menuicon"]:checked + label span:nth-child(1) {
  top: 50%;
  transform: translateY(-50%) rotate(45deg);
}
input[id="menuicon"]:checked + label span:nth-child(2) {
  opacity: 0;
}
input[id="menuicon"]:checked + label span:nth-child(3) {
  bottom: 50%;
  transform: translateY(50%) rotate(-45deg);
}
div[class="sidebar"] {
  width: 300px;
  height: 100%;
  background: rgb(255, 255, 255);
  position: fixed;
  top: 0;
  right: -300px;
  z-index: 1;
  transition: all 0.35s;
}
input[id="menuicon"]:checked + label + div {
  right: 0;
}
</style>
