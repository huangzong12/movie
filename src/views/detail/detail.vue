<template>
  <transition name="detail">
    <div class="detail">
      <h1>详情页{{$route.params.id}}</h1>
    </div>
  </transition>
</template>

<style lang="stylus" scoped>
  .detail
    position fixed
    top 0
    bottom 0
    width 100%
    background #fff
    z-index: 10
  .detail-enter-active, .detail-leave-active
    transition all .5s
  .detail-enter, .detail-leave-to
    transform translateX(100%)
</style>