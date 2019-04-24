<template>
  <div  class="header">
    <div class="back">
      <i class="iconfont icon-zuojiantou"></i>
    </div>
    <div class="midd">
      <i class="iconfont icon-sousuo"></i>
      <input type="text" placeholder="输入城市/景点/游玩主题">
    </div>
    <div class="end">
      北京<i class="iconfont icon-xiajiantou"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'index-header'
}
</script>

<style lang="stylus" scoped>
    @import "../../assets/stylus/varibles.styl";
    @import "../../assets/css/iconfont/iconfont.css";
    .header
        display: flex
        height: .88rem
        line-height: .88rem
        background: $bgColor
       .back
         width: .58rem
         text-align: center
         color: #fff
        .midd
          flex: 1
          display: flex
          align-items: center
          i
            padding  0.05rem
            padding-left  0.1rem
            padding-right  0.1rem
            margin-left 0.2rem
            font-size 19px
            background #ffffff
            width .45rem
            height .58rem
            line-height .58rem
            border 0
            color #ccc
            border-top-left-radius  .1rem
            border-bottom-left-radius  .1rem
            font-weight bold
          input
            flex 1
            border 0
            height .58rem
            padding 0.05rem 0
            border-bottom-right-radius .1rem
            border-top-right-radius  .1rem
        .end
          width: 1.5rem
          color: #fff
          text-align: center
</style>
