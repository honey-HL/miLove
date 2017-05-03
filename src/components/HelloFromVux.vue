<!--<template>-->
  <!--<div class="content">-->

      <!--<flexbox :gutter="0">-->
        <!--<flexbox-item>-->
          <!--<swiper loop :list="demo06_list" :index="demo06_index" @on-index-change="demo06_onIndexChange" dots-position="center"></swiper>-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->
      <!--<flexbox class="dynamics">-->
        <!--<flexbox-item class="flex-demo" :span="1/4">个人动态</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/img1.png" alt="">-->
        <!--</flexbox-item >-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/img1.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/img1.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/img1.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item style="margin-left:35px;">-->
          <!--<img src="../images/icon_grxq_click@2x.png" alt="" style="width:15px;height:15px;">-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->
      <!--<flexbox class="dynamics" style="margin-top: 10px;">-->
        <!--<flexbox-item class="flex-demo" :span="1/4">秘密相册</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/secret.png" alt="">-->
        <!--</flexbox-item >-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/secret.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/secret.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item class="flex-demo top" :span="1/8">-->
          <!--<img src="../images/secret.png" alt="">-->
        <!--</flexbox-item>-->
        <!--<flexbox-item style="margin-left:35px;">-->
          <!--<img src="../images/icon_grxq_click@2x.png" alt="" style="width:15px;height:15px;">-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->
      <!--<flexbox class="main">-->
        <!--<flexbox-item class="flex-demo">-->
          <!--<flexbox  style="align-items: flex-start;margin-top: 23px;">-->
              <!--<flexbox-item :span="1/10" class="flex-demo">-->
                <!--<div><img src="../images/icon_grxq_positioning-@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
              <!--</flexbox-item>-->
              <!--<flexbox-item>-->
                  <!--<p>经常去的五个地方</p>-->
                  <!--<p>新希望国际B座，银泰城，大源公交站</p>-->
                  <!--<p>倪家桥，五大花园</p>-->
              <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox  style="align-items: flex-start;margin-top: 23px;">-->
              <!--<flexbox-item :span="1/10" class="flex-demo">-->
                <!--<div><img src="../images/icon_grxq_background-@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
              <!--</flexbox-item>-->
              <!--<flexbox-item>-->
                <!--<p>工作与教育背景</p>-->
                <!--<p>销售，月收入10000，本科</p>-->
              <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox style="align-items: flex-start;margin-top: 23px;">-->
              <!--<flexbox-item :span="1/10" class="flex-demo">-->
                <!--<div><img src="../images/icon_grxq_received-gift@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
              <!--</flexbox-item>-->
              <!--<flexbox-item>-->
                <!--<p>收到的礼物</p>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/4">-->
                    <!--<button style="width:80px;height: 80px;" @click="sendGift"><img src="../images/icon_add-_gift@2x.png" alt="" style="width:80px;height: 80px;"></button>-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item style="color: rgb(140,117,250)">-->
                    <!--赠与礼物，马上开始聊天-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
              <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox style="align-items: flex-start;margin-top: 23px;">-->
              <!--<flexbox-item :span="1/10" class="flex-demo">-->
                <!--<div><img src="../images/icon_grxq_hobby-@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
              <!--</flexbox-item>-->
              <!--<flexbox-item>-->
                <!--<p>爱好</p>-->
              <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox style="align-items: flex-start;margin-top: 23px;">-->
              <!--<flexbox-item :span="1/10" class="flex-demo">-->
                <!--<flexbox>-->
                  <!--<flexbox-item class="flex-demo">-->
                    <!--<div><img src="../images/icon_grxq_we@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
              <!--</flexbox-item>-->
              <!--<flexbox-item class="flex-demo">-->
                <!--<flexbox>-->
                  <!--<flexbox-item>-->
                    <!--<p>关于我</p>-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                    <!--<flexbox-item :span="1/5" class="colorgray">-->
                      <!--恋爱方式-->
                    <!--</flexbox-item>-->
                    <!--<flexbox-item>-->
                      <!--我的恋爱方式是开放式的-->
                    <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--星座-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                   <!--狮子座-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--性取向-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--我爱异性-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--外貌-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--180cm,66kg,均匀，肤白，黑头发-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--住房情况-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--有住房-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--子女情况-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--无子女-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--吸烟与否-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--偶尔会吸，无烟瘾-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5" class="colorgray">-->
                    <!--饮酒与否-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--有时应酬会喝点-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
              <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox style="align-items: flex-start;margin-top: 23px;">-->
            <!--<flexbox-item :span="1/10" class="flex-demo">-->
              <!--<div><img src="../images/icon_grxq_language-@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
            <!--</flexbox-item>-->
            <!--<flexbox-item>-->
                <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5">-->
                    <!--语言-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                    <!--中文，英文（流利）-->
                  <!--</flexbox-item>-->
                <!--</flexbox>-->
            <!--</flexbox-item>-->
          <!--</flexbox>-->
          <!--<flexbox style="align-items: flex-start;margin-top: 23px;">-->
            <!--<flexbox-item :span="1/10" class="flex-demo">-->
              <!--<div><img src="../images/icon_grxq_certification@2x.png" alt="" style="width:25px;height: 25px;"></div>-->
            <!--</flexbox-item>-->
            <!--<flexbox-item>-->
              <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5">-->
                    <!--实名认证-->
                  <!--</flexbox-item>-->
              <!--</flexbox>-->
              <!--<flexbox>-->
                  <!--<flexbox-item :span="1/5">-->
                    <!--<img src="../images/icon_grxq_identity-@2x.png" alt="" style="width:60px;height: 60px;">-->
                  <!--</flexbox-item>-->
                  <!--<flexbox-item>-->
                      <!--<flexbox>-->
                          <!--<flexbox-item>-->
                            <!--身份认证-->
                          <!--</flexbox-item>-->
                      <!--</flexbox>-->
                      <!--<flexbox>-->
                        <!--<flexbox-item>-->
                          <!--已认证-->
                        <!--</flexbox-item>-->
                      <!--</flexbox>-->
                  <!--</flexbox-item>-->
              <!--</flexbox>-->
            <!--</flexbox-item>-->
          <!--</flexbox>-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->

  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--import { Group, Cell, Flexbox, FlexboxItem, Swiper, SwiperItem, Scroller } from 'vux'-->

  <!--const baseList = [{-->
    <!--url: 'javascript:',-->
    <!--img: 'https://static.vux.li/demo/1.jpg',-->
    <!--title: '送你一朵fua'-->
  <!--}, {-->
    <!--url: 'javascript:',-->
    <!--img: 'https://static.vux.li/demo/2.jpg',-->
    <!--title: '送你一辆车'-->
  <!--}, {-->
    <!--url: 'javascript:',-->
    <!--img: 'https://static.vux.li/demo/3.jpg',-->
    <!--title: '送你一次旅行'-->
  <!--}]-->

  <!--const urlList = baseList.map((item, index) => ({-->
    <!--url: 'http://m.baidu.com',-->
    <!--img: item.img,-->
    <!--title: `(可点击)${item.title}`-->
  <!--}))-->

  <!--export default {-->
    <!--components: {-->
      <!--Group,-->
      <!--Cell,-->
      <!--Flexbox,-->
      <!--FlexboxItem,-->
      <!--Swiper,-->
      <!--SwiperItem,-->
      <!--Scroller-->
    <!--},-->
    <!--data () {-->
      <!--return {-->
        <!--demo06_list: urlList,-->
        <!--demo06_index: 0-->
      <!--}-->
    <!--},-->
    <!--methods: {-->
      <!--demo06_onIndexChange (index) {-->
        <!--this.demo06_index = index-->
      <!--},-->
      <!--sendGift () {-->
        <!--window.webkit.messageHandlers.Share.postMessage(null)-->
      <!--}-->
    <!--}-->
<!--}-->
<!--</script>-->

<!--<style>-->
  <!--.black {-->
    <!--background-color: #000;-->
  <!--}-->
  <!--.title{-->
    <!--line-height: 100px;-->
    <!--text-align: center;-->
    <!--color: #fff;-->
  <!--}-->
  <!--.animated {-->
    <!--animation-duration: 1s;-->
    <!--animation-fill-mode: both;-->
  <!--}-->
  <!--@-webkit-keyframes fadeInUp {-->
    <!--from {-->
      <!--opacity: 0;-->
      <!--transform: translate3d(0, 100%, 0);-->
    <!--}-->
    <!--100% {-->
      <!--opacity: 1;-->
      <!--transform: none;-->
    <!--}-->
  <!--}-->
  <!--@keyframes fadeInUp {-->
    <!--from {-->
      <!--opacity: 0;-->
      <!--transform: translate3d(0, 100%, 0);-->
    <!--}-->
    <!--100% {-->
      <!--opacity: 1;-->
      <!--transform: none;-->
    <!--}-->
  <!--}-->
  <!--.fadeInUp {-->
    <!--animation-name: fadeInUp;-->
  <!--}-->
  <!--.logo {-->
    <!--width: 100px;-->
    <!--height: 100px-->
  <!--}-->
  <!--.dynamics{-->
    <!--height: 57px;-->
    <!--line-height: 57px;-->
    <!--margin-top: 0px;-->
    <!--background-color:#fff;-->
    <!--display: flex;-->
  <!--}-->
  <!--.dynamics img{-->
    <!--width: 47px;-->
    <!--height:47px;-->
    <!--display: block;-->
  <!--}-->
  <!--.content{-->
    <!--background:rgb(238,238,239);-->
  <!--}-->
  <!--.flex-demo{-->
    <!--text-align: center;-->
  <!--}-->
  <!--.dynamics .top{-->
    <!--margin-top: 2px;-->
  <!--}-->
  <!--.main{-->
    <!--margin-top: 14px;-->
    <!--background: #fff;-->
  <!--}-->
 <!--.colorgray{-->
   <!--color: rgb(153,153,153);-->
 <!--}-->
  <!--. my-white {-->
    <!--background-color: #fff;-->
  <!--}-->
  <!--. active{-->
    <!--background-color: #999;-->
  <!--}-->
  <!--button{-->
    <!--border: none;-->
    <!--background-color: #fff;-->
  <!--}-->
<!--</style>-->



<!--/........................................同城首页............................................................./-->
<!--<template>-->
  <!--<div class="content">-->
    <!--<flexbox wrap="wrap" :gutter="0">-->
      <!--<flexbox style="margin-bottom: 3%;">-->
        <!--<flexbox-item>-->
          <!--<img src="../images/banner_sy_shuffling-@2x.png" alt="">-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->
      <!--<flexbox-item :span='5' v-for="(item,index) in baseList" :key="index" style="padding-left: 5.5%;padding-top: 2%;">-->
        <!--<div>-->
          <!--<img :src="item.img" alt="" style="width:100%;display: block;">-->
        <!--</div>-->
        <!--<div style="background: #fff;padding-top: 3%;">-->
          <!--<span style="padding-left: 5%;color: #3e3e3e;font-size: 14px;">{{item.name}}</span>-->
          <!--<span><img :src="item.dot" alt=""style="width: 20%;display: inline-block"></span>-->
        <!--</div>-->
        <!--<div style="background: #fff;padding-bottom: 2%;">-->
          <!--<span v-if="flag == '0'" style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.place}}</span>-->
          <!--<span v-else-if="flag == '1'" style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.time}}</span>-->
          <!--<span v-else style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.distance}}</span>-->
          <!--<span v-if="flag == '0'" style="color: rgb(153,153,153);font-size: 10px;padding-left: 57%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
          <!--<span v-else-if="flag == '1'" style="color: rgb(153,153,153);font-size: 10px;padding-left: 34%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
          <!--<span v-else style="color: rgb(153,153,153);font-size: 10px;padding-left: 54%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
        <!--</div>-->
      <!--</flexbox-item>-->
    <!--</flexbox>-->
    <!--<flexbox wrap="wrap" :gutter="0" style="padding-bottom: 4%;">-->
      <!--<flexbox style="margin-top: 3%;padding-bottom: 1%;">-->
        <!--<flexbox-item>-->
          <!--<img src="../../static/img/banner_sy@2x.png" alt="">-->
        <!--</flexbox-item>-->
      <!--</flexbox>-->
      <!--<flexbox-item :span='5' v-for="(item,index) in secondList" :key="index" style="padding-left: 5.5%;padding-top: 2%;">-->
        <!--<div>-->
          <!--<img :src="item.img" alt="" style="width:100%;display: block;">-->
        <!--</div>-->
        <!--<div style="background: #fff;padding-top: 3%;">-->
          <!--<span style="padding-left: 5%;color: #3e3e3e;font-size: 14px;">{{item.name}}</span>-->
          <!--<span><img :src="item.dot" alt=""style="width: 20%;display: inline-block"></span>-->
        <!--</div>-->
        <!--<div style="background: #fff;padding-bottom: 2%;">-->
          <!--<span v-if="flag == '0'" style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.place}}</span>-->
          <!--<span v-else-if="flag == '1'" style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.time}}</span>-->
          <!--<span v-else style="padding-left: 5%;color: #3e3e3e;color: rgb(102,102,102);font-size: 12px;">{{item.distance}}</span>-->
          <!--<span v-if="flag == '0'" style="color: rgb(153,153,153);font-size: 10px;padding-left: 57%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
          <!--<span v-else-if="flag == '1'" style="color: rgb(153,153,153);font-size: 10px;padding-left: 30%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
          <!--<span v-else style="color: rgb(153,153,153);font-size: 10px;padding-left: 54%;">-->
            <!--<img :src="item.camera" alt=""style="width: 8%;display: inline-block;">&nbsp;6-->
          <!--</span>-->
        <!--</div>-->
      <!--</flexbox-item>-->
    <!--</flexbox>-->
  <!--</div>-->
<!--</template>-->
<!--<script>-->
  <!--import { Flexbox, FlexboxItem, querystring } from 'vux'-->
  <!--const baseList = [-->
    <!--{-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture-_one@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'IHIGIHIN',-->
      <!--place: '北京',-->
      <!--distance: '365m',-->
      <!--time: '50分钟前'-->
    <!--}, {-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture_two@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'SUNSHINE',-->
      <!--place: '四川',-->
      <!--distance: '3.5km',-->
      <!--time: '今天12：02'-->
    <!--}, {-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture_three@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'IHIGIHIN',-->
      <!--place: '广东',-->
      <!--distance: '500m',-->
      <!--time: '昨天17:05'-->
    <!--}, {-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture_four-@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'IHIGIHIN',-->
      <!--place: '湖南',-->
      <!--distance: '900m',-->
      <!--time: '昨天12:51'-->
    <!--}-->
  <!--]-->
  <!--const secondList = [-->
    <!--{-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture_five-@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'IHIGIHIN',-->
      <!--place: '北京',-->
      <!--distance: '1.2km',-->
      <!--time: '04-01 17:40'-->
    <!--}, {-->
      <!--url: 'javascript:',-->
      <!--img: '../../static/img/botton_sy_picture_six-@2x.png',-->
      <!--camera: '../../static/img/icon_sy_camera-@2x.png',-->
      <!--dot: '../../static/img/icon_sy_vip@2x.png',-->
      <!--name: 'IHIGIHIN',-->
      <!--place: '四川',-->
      <!--distance: '1.8km',-->
      <!--time: '04-05 18:40'-->
    <!--}-->
  <!--]-->
  <!--export default {-->
    <!--components: {-->
      <!--Flexbox,-->
      <!--FlexboxItem,-->
      <!--querystring-->
    <!--},-->
    <!--data () {-->
      <!--return {-->
        <!--baseList: baseList,-->
        <!--secondList: secondList,-->
        <!--flag: ''-->
      <!--}-->
    <!--},-->
    <!--mounted: function () {-->
      <!--this.getUrlKey()-->
    <!--},-->
    <!--methods: {-->
      <!--getUrlKey () {-->
        <!--let hash = location.hash-->
        <!--if (hash.indexOf('?') !== -1) {-->
          <!--this.flag = hash.substr(3).split('=')[1]-->
        <!--}-->
      <!--}-->
    <!--}-->
  <!--}-->
<!--</script>-->
<!--<style>-->
  <!--dl,dt,dd{-->
    <!--margin: 0;    padding: 0;    border: 0;    font-size: 100%;    font: inherit;    vertical-align: baseline;-->
  <!--}-->
  <!--body{-->
    <!--background: rgb(238,238,239);-->
  <!--}-->
  <!--img{-->
    <!--width:100%;-->
    <!--height: auto;-->
    <!--border-style: none;-->
    <!--display: block;-->
  <!--}-->
  <!--button,-->
  <!--input {-->
    <!--overflow: visible;-->
  <!--}-->
  <!--.classA{-->
    <!--padding-left: 3%;-->
  <!--}-->
  <!--.classB{-->
    <!--padding-right: 3%;-->
  <!--}-->
<!--</style>-->

<!--/........................................魅力榜富豪榜............................................................./-->
<template>
  <div class="content">
    <flexbox wrap="wrap" :gutter="0">
      <flexbox class="box" style="margin-top: 2%;" >
        <flexbox-item>
          <span>实时榜</span>
          <span>
            <img src="../../static/img/icon_sy_arrow-@2x.png" alt="" style="width:10px;display: inline-block">
          </span>
        </flexbox-item>
      </flexbox>
      <flexbox class="box" style="padding-top: 5%;margin-bottom: 2%;padding-bottom: 5%;">
        <flexbox-item style="padding-left: 5%;">
            <div style="position: relative">
                <span>
                  <img src="../../static/img/icon_sy_ranking_two@2x.png" alt="" style="width:85%;">
                </span>
                <span style="position: absolute;top:12%;left:39%;font-size:12px;">2</span>
                <span style="position: absolute;top:30%;left: 10%;">
                  <img :src="topThreeList[0].img" style="border-radius: 50%;width: 70%;">
                </span>
            </div>
            <dl style="margin-top: 20%;text-align: center;">
                <dt>{{topThreeList[0].name}}</dt>
                <dd style="width:35px;height: 15px;background: rgb(240,117,130);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                  <img src="../../static/img/icon_grxq_boy@2x.png" alt="" style="width:30%;margin-top: 5%;margin-left:5%;display: inline;">
                  {{topThreeList[0].age}}
                </dd>
                <dd style="width:35px;height: 15px;background: rgb(140,117,250);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                  VIP
                </dd>
                <dd style="width:35px;height: 15px;background: rgb(250,170,117);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                 魅10
                </dd>
            </dl>
        </flexbox-item>
        <flexbox-item style="padding-right: 2%;margin-top: -5%;">
            <div style="position: relative;">
                <span>
                  <img src="../../static/img/icon_sy_ranking_one@2x.png" alt="" style="width:100%;">
                </span>
                <span style="position: absolute;top:12%;left:48%;font-size:12px;">1</span>
                <span style="position: absolute;top:25%;left: 10%;">
                  <img :src="topThreeList[1].img" style="border-radius: 50%;width: 90%;">
                </span>
            </div>
            <dl style="margin-top: 20%;text-align: center;margin-left: -6%;">
                <dt>{{topThreeList[1].name}}</dt>
                <dd style="width:35px;height: 15px;background: rgb(240,117,130);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                  <img src="../../static/img/icon_grxq_boy@2x.png" alt="" style="width:30%;margin-top: 5%;margin-left:5%;display: inline;">
                  {{topThreeList[1].age}}
                </dd>
                <dd style="width:35px;height: 15px;background: rgb(140,117,250);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                  VIP
                </dd>
                <dd style="width:35px;height: 15px;background: rgb(250,170,117);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                  魅10
                </dd>
            </dl>
        </flexbox-item>
        <flexbox-item style="padding-left: 3%;">
            <div style="position: relative">
                <span>
                  <img src="../../static/img/icon_sy_ranking_three@2x.png" alt="" style="width:85%;">
                </span>
                <span style="position: absolute;top:12%;left:39%;font-size:12px;">3</span>
                <span style="position: absolute;top:35%;left: 5%;">
                  <img :src="topThreeList[2].img" style="border-radius: 50%;width: 80%;">
                </span>
            </div>
            <dl style="margin-top: 20%;text-align: center;margin-left: -35%;">
                <dt>{{topThreeList[2].name}}</dt>
              <dd style="width:35px;height: 15px;background: rgb(240,117,130);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                <img src="../../static/img/icon_grxq_boy@2x.png" alt="" style="width:30%;margin-top: 5%;margin-left:5%;display: inline;">
                {{topThreeList[2].age}}
              </dd>
              <dd style="width:35px;height: 15px;background: rgb(140,117,250);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                VIP
              </dd>
              <dd style="width:35px;height: 15px;background: rgb(250,170,117);border-radius:5px;display: inline-block;color: #fff;font-size: 12px;line-height: 15px;">
                魅10
              </dd>
            </dl>
        </flexbox-item>
      </flexbox>
      <flexbox v-for="(item,index) in otherList" :key="index" wrap="wrap" :gutter="0" class="box">
        <flexbox :gutter="0" style="height:120px;">
          <flexbox-item :span='1' style="color: rgb(140,117,250);text-align: center;">
            4
          </flexbox-item>
          <flexbox-item :span='3'>
            <img :src="item.img" alt="" style="width: 80%;border-radius: 50%;">
          </flexbox-item>
          <flexbox-item style="border-bottom: 1px solid #ccc;padding-bottom: 3%;">
            <p>1</p>
            <p>1</p>
            <p>1</p>
          </flexbox-item>
        </flexbox>
      </flexbox>
    </flexbox>
  </div>
</template>
<script>
  import { Flexbox, FlexboxItem, Cell, Group } from 'vux'
  const topThreeList = [
    {
      url: 'javascript:',
      img: '../../static/img/top2.png',
      name: 'Whitney',
      age: '24'
    }, {
      url: 'javascript:',
      img: '../../static/img/top1.png',
      name: 'Katharine',
      age: '22'
    }, {
      url: 'javascript:',
      img: '../../static/img/top3.png',
      name: 'William',
      age: '25'
    }
  ]
  const otherList = [
    {
      url: 'javascript:',
      img: '../../static/img/botton_sy_picture_two@2x.png',
      name: 'Whitney',
      age: '24'
    }, {
      url: 'javascript:',
      img: '../../static/img/botton_sy_picture-_one@3x.png',
      name: 'Whitney',
      age: '24'
    }, {
      url: 'javascript:',
      img: '../../static/img/botton_sy_picture_four-@2x.png',
      name: 'Whitney',
      age: '24'
    }, {
      url: 'javascript:',
      img: '../../static/img/botton_sy_picture_three@2x.png',
      name: 'Whitney',
      age: '24'
    }
  ]
  export default{
    components: {
      Flexbox,
      FlexboxItem,
      Cell,
      Group
    },
    data () {
      return {
        topThreeList: topThreeList,
        otherList: otherList
      }
    },
    methods: {
    },
    mounted: function () {
    }
  }
</script>
<style>
  body{margin: 0;padding: 0;vertical-align: baseline;}
  .content{
    background: rgb(238,238,239);
  }
  .box{
    background: #fff;
    margin-left: 0;
  }
  img{
    width: 100%;
    height: auto;
    border-style: none;
    display: block;
  }
</style>
