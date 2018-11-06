<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide>
        <img class="swiper-img" src="http://img1.qunarzz.com/piao/fusion/1809/31/da037478f37cf202.jpg_750x200_a02cf862.jpg" alt="">
      </swiper-slide>
      <swiper-slide>
        <img class="swiper-img" src="http://img1.qunarzz.com/piao/fusion/1810/6e/4a5551bbb189d902.jpg_750x200_25257467.jpg" alt="">
      </swiper-slide>
      <swiper-slide>
        <img  class="swiper-img" src="http://img1.qunarzz.com/piao/fusion/1809/d4/e298dff35d3af802.jpg_750x200_9b0d56c1.jpg" alt="">
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination"  slot="pagination"></div>
      <!-- <div class="swiper-button-prev" slot="button-prev"></div>
      <div class="swiper-button-next" slot="button-next"></div>
      <div class="swiper-scrollbar"   slot="scrollbar"></div> -->
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination'
      }
    }
  }
}
</script>

<style lang="stylus" scoped>
.wrapper >>> .swiper-pagination-bullet-active
  background #fff !important
.swiper-container
  width 100%
  height 0
  overflow hidden
  padding-bottom 26.7%
  .swiper-img
    width 100%
</style>
