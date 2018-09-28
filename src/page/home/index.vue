<template>
  <div class="home_container">
    <!--<test-slot >-->
      <!--<div slot="one">-->
        <!--<span>one</span>-->
        <!--<span>第一个</span>-->
      <!--</div>-->
      <!--<div><span>此div没有用slot指定名字所以会换掉没有名字的属性slot标签</span></div>-->
      <!--<div slot="two">-->
        <!--<span>two</span>-->
        <!--<span>第二个</span>-->
      <!--</div>-->
    <!--</test-slot>-->



    <itemcontainer father-component="home"></itemcontainer>
  </div>
</template>

<script>
  import itemcontainer from '../../components/itemcontainer'
  // import TestSlot from '../../components/header/testSlot'

  export default {
    name: 'home',
    components: {
      itemcontainer
    },
    // components: {TestSlot},
    created() {

    }
  }
</script>

<style lang="less" scoped>
  .home_container {
    color: #FFF;
    font-size: 12px;
  }
</style>
