<template>
  <div id="app">
    <test-slot >
      <div slot="one">
        <span>one</span>
        <span>第一个</span>
      </div>
      <div><span>此div没有用slot指定名字所以会换掉没有名字的属性slot标签</span></div>
      <div slot="two">
        <span>two</span>
        <span>第二个</span>
      </div>
    </test-slot>
    <router-view></router-view>
  </div>
</template>

<script>
  // import headerTop from './components/header/headerTop'


  export default {

    data() {

    }
  }

</script>

<style lang="less" scoped>
  .home_container {
    color: #FFF;
    font-size: 12px;
  }
</style>
