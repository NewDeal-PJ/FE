<template>
<Header></Header>
  <div>
    <a id="custom-login-btn" @click="kakaoLogin()">
        <img src="http://papaspick.com/web/upload/2019_web/icon/kakao_login.jpg" width="222"
        />
      </a>
  </div>
</template>

<script>

import Header from 'src/components/Home/Header.vue';

export default{
    components: { Header }
}</script>

<style></style>
