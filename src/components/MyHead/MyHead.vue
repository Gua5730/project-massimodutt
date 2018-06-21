<template>
    <div class="header">
      <div class="header-left">
        <i class="iconfont icon-menu2"></i>
      </div>
      <div class="header-center"></div>
      <div class="header-right">
        <div class="header-search">
          <i class="iconfont icon-gouwuche"></i>
        </div>
        <div class="header-shopping-cart">
          <i class="iconfont icon-suosou"></i>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "MyHead"
    }
</script>

<style lang="less" scoped>
  .iconfont {
    font-size: 36px;
    color: #505252;
  }
  .header {
    position: fixed;
    top: 0;
    width: 100%;
    height: 104px;
    background: red;
    .header-left {
      float: left;
      font-size: 24px;
      padding: 34px 28px;
      /*border: 1px solid lightgreen;*/
    }
    .header-center{
      width: 300px;
      height: 42px;
      position: absolute;
      left: 50%;
      top: 38px;
      margin-left: -150px;
      /*border: 1px solid cyan;*/
      background: url("logo.png") no-repeat;
      background-size: 100% 100%;
    }
    .header-right{
      float: right;
      width: auto;
      .header-search,.header-shopping-cart{
        float: right;
        padding: 34px 28px;
        /*border: 1px solid;*/
      }
    }
  }
</style>
