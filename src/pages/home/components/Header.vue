<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
  .header
    display: flex
    line-height: .86rem
    background: $bgColor
    color: #fff
    .header-left
      width: .64rem
      float: left
      padding-left: .2rem
    .header-input
      flex: 1
      height: .64rem
      line-height: .64rem
      background: #ffffff
      color: #ccc
      margin-top: .12rem
      margin-left: .1rem
      margin-right: .2rem
      border-radius: .1rem
      padding-left: .2rem
    .header-right
      width: 1.24rem
      float: right
</style>
