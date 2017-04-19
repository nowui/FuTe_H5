<template>
  <div class="index">
      <div class="logo"></div>
      <div class="fute"></div>
      <div class="ouxi"></div>
      <div class="pinpai" @click="handleVideo()"></div>
      <div class="jingmei" @click="handlePhoto()"></div>
      <div class="shijia" @click="handleVote()"></div>
      <div class="daodian"></div>
    </div>
</template>

<script>
  import 'weui';
  import weui from 'weui.js';

  export default {
    data () {
      return {

      }
    },
    created () {

    },
    mounted () {

    },
    beforeDestroy () {

    },
    methods: {
      handleVideo: function () {
        this.$router.push('video');
      },
      handlePhoto: function () {
        this.$router.push('photo');
      },
      handleVote: function () {
        this.$router.push('vote');
      }
    }
  }
</script>

<style scoped>
  .index {
    position: absolute;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    background-image: url('/static/image/index_bg.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .logo {
    position: absolute;
    top: 0px;
    right: 40px;
    width: 132px;
    height: 80px;
    background-image: url('/static/image/logo.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: down 0.5s linear;
    -webkit-animation-delay: 0.25s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .fute {
    position: absolute;
    top: 170px;
    left: 50%;
    margin-left: -310px;
    width: 321px;
    height: 55px;
    background-image: url('/static/image/fute.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: down 0.5s linear;
    -webkit-animation-delay: 0.5s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .ouxi {
    position: absolute;
    top: 280px;
    left: 50%;
    margin-left: -310px;
    width: 621px;
    height: 73px;
    background-image: url('/static/image/ouxi.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: down 0.5s linear;
    -webkit-animation-delay: 0.75s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .pinpai {
    position: absolute;
    top: 434px;
    left: 50%;
    margin-left: -350px;
    width: 304px;
    height: 74px;
    background-image: url('/static/image/pinpai.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: right 0.5s linear;
    -webkit-animation-delay: 1s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .jingmei {
    position: absolute;
    top: 434px;
    left: 50%;
    margin-left: 42px;
    width: 304px;
    height: 74px;
    background-image: url('/static/image/jingmei.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: left 0.5s linear;
    -webkit-animation-delay: 1s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .shijia {
    position: absolute;
    top: 1070px;
    left: 50%;
    margin-left: -206px;
    width: 412px;
    height: 78px;
    background-image: url('/static/image/shijia.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: up 0.5s linear;
    -webkit-animation-delay: 1.25s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

  .daodian {
    position: absolute;
    top: 1200px;
    left: 50%;
    margin-left: -206px;
    width: 412px;
    height: 19px;
    background-image: url('/static/image/daodian.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0;
    -webkit-animation: up 0.5s linear;
    -webkit-animation-delay: 1.5s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
  }

</style>
