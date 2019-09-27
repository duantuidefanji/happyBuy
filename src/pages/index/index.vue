<template>
  <div id="container">
    <!-- 搜索栏 -->
    <div class="searchbox"><input type="text"/></div>
    <!-- banner 轮播图 -->
    <swiper class="banner" circular indicator-dots indicator-color="rgba(255, 255, 255, 0.6)" indicator-active-color="#fff">
      <swiper-item>
        <a href="">
          <img src="/static/uploads/banner1.png" />
        </a>
      </swiper-item>
      <swiper-item>
        <a href="">
          <img src="/static/uploads/banner2.png" />
        </a>
      </swiper-item>
      <swiper-item>
        <a href="">
          <img src="/static/uploads/banner3.png" />
        </a>
      </swiper-item>
    </swiper>

    <!-- 导航条 -->
    <div class="navs">
      <a href="">
        <img src="/static/uploads/icon_index_nav_1@2x.png" />
      </a>
      <a href="">
        <img src="/static/uploads/icon_index_nav_2@2x.png" />
      </a>
      <a href="">
        <img src="/static/uploads/icon_index_nav_3@2x.png" />
      </a>
      <a href="">
        <img src="/static/uploads/icon_index_nav_4@2x.png" />
      </a>
    </div>
  </div>
</template>
<script>
import card from '@/components/card'

export default {
}
</script>

<style scoped lang='less'>
#container{
width:750rpx;
}
.searchbox{
  width:100%;
  box-sizing: border-box;
  height:82rpx;
  background-color: #EB4551;
  padding:0 30rpx;
  input {
    height:60rpx;
     background-color:#fff;
  }
}
.banner {
  width: 100%;
  height: 340rpx;

  img {
    width: 100%;
    height: 340rpx;
  }
 }
 .navs {
    display: flex;
    justify-content: space-between;
    padding: 30rpx 44rpx;

   a{
     display:block;
      width: 128rpx;
      height: 140rpx;
    }
  }

</style>
