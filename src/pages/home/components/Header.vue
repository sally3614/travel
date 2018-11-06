<template>
  <div class="header">
    <div class="header-left">
      <i class="iconfont back-icon">&#xe624;</i>
    </div>
    <div class="center">
      <i class="iconfont search">&#xe632;</i>
      输入城市经典主题
    </div>
    <div class="header-right">
      <div class="name">城市</div>
      <i class="iconfont arrow-icon">&#xe639;</i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~stylesurl/mixins.styl';
.header
  width 100%
  display flex
  height .86rem
  background #00bcd4
  color #fff
  .header-left
    width .64rem
    text-align center
    line-height .86rem
    .back-icon
      font-size .4rem
      font-weight bold
  .header-right
    padding 0 .22rem
    text-align center
    box-sizing border-box
    line-height .86rem
    font-size 0
    .name
      display inline-block
      max-width 1.4rem
      font-size .28rem
      ellipsis()
    .arrow-icon
      vertical-align top
      font-size .28rem
  .center
    flex 1
    height .62rem
    line-height .62rem
    margin-top .12rem
    background #ffffff
    border-radius .08rem
    padding-left .1rem
    color #ccc
</style>
