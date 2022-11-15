<template>
  <div id="pf">
    <div id="jeong" class="box">
      <h1 class="name">정우성 ㅣ 정후보</h1>

      <img class="photo" src="../assets/images/people/jeong.png" />
      <img class="profile" src="../assets/images/people/jeong-profile.png" />
    </div>
    <div id="kim" class="box">
      <h1 class="name">김기범 ㅣ 부후보</h1>

      <img class="photo" src="../assets/images/people/kim.png" />
      <img class="profile" src="../assets/images/people/kim-profile.png" />
    </div>
  </div>
</template>

<style>
.photo {
  width: 30%;
  display: block;
  margin: auto;
  border-radius: 10px;
  margin-top: 5px;
  margin-bottom: 5px;
}

h1.name {
  font-size: 20px;
  text-align: center;
  padding-top: 20px;
  padding: 10px 0px 10px 0px;
  font-weight: 900;
  position: relative;
  background-color: rgb(235, 235, 235, 0);
}

h1.name:before,
h1.name:after {
  content: "[";
  display: inline-block;
  position: relative;
  top: 1px;
  height: 100%;
  font-size: 1.4em;
  color: rgb(236, 213, 78);

  transition: all 0.5s ease;
  transform: translateX(-5px);
}

h1.name:after {
  content: "]";
  transform: translateX(5px);
}

h1.name:hover:before {
  transform: translateX(-10px);
}

h1.name:hover:after {
  transform: translateX(10px);
}

.box {
  margin: 12px;
  text-align: center;
  /* background-image: linear-gradient(
    to bottom,
    rgb(236, 213, 78) 33%,
    rgb(235, 235, 235) 33%,
    rgb(235, 235, 235) 33%
  ); */
  background-color: rgb(235, 235, 235);
  border-radius: 10px;
}

.profile {
  margin-top: 15px;
  padding-top: 8px;
  padding-bottom: 8px;
  width: 90%;
  background-color: rgb(235, 235, 235, 0);
  border-top: 1.6px solid rgb(48, 48, 48);
}
</style>
