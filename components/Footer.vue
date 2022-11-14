<template>
  <div class="footer">
    <div class="logo">
      제 13대 한양대학교 약학대학 학생회
      <br />
      선거운동본부 하이브[HY:BE]
    </div>
    <!-- <div class="sns">
      <div class="kakao icon">
        <img src="../assets/images/icon-kakao.png" />
        <span>카카오톡 채널</span>
      </div>

      <div class="insta icon">
        <img src="../assets/images/icon-instagram.png" />
        <span>인스타그램</span>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  word-break: keep-all;
  background-color: rgb(87, 87, 87);
  justify-content: space-between;
  align-items: center;
  font-weight: 500;
  text-align: center;
  padding: 30px;
  font-size: 15px;
  letter-spacing: -0.3px;
  word-spacing: -0.5px;
  margin: 0;
  border: 0;
}
.logo {
  margin-top: 5px;
  text-align: center;
  box-sizing: content-box;
  padding: 0 12px;
  height: 100%;
  color: white;
  background-color: transparent;
}

a {
  color: var(--theme-link-color);
  text-decoration: none;
  cursor: pointer;
}

.sns {
  color: white;
  display: inline-block;
  margin-top: 10px;
  align-items: center;
  outline: none;
  cursor: pointer;
  font-size: 14.5px;
}
.kakao:hover {
  opacity: 0.7;
}

.insta:hover {
  opacity: 0.7;
}

.icon {
  display: inline;
}

.icon img {
  vertical-align: middle;
  width: 24px;
}

span {
  margin-left: 3px;
  margin-right: 6px;
}
</style>
