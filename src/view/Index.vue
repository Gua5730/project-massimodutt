<template>
  <div>
    <!--<my-head></my-head>-->
    <div class="index-wrapper">
      <div class="tab">
        <div class="tab-item">女装</div>
        <div class="tab-item">男装</div>
        <div class="tab-item">女童装</div>
        <div class="tab-item">男童装</div>
      </div>
    </div>
  </div>
</template>

<script>
  import MyHead from '../components/MyHead/MyHead'
  import MyFooter from '../components/MyFoot/MyFoot'
  export default {
    name: "Index",
    components: {
      MyHead,
      MyFooter
    }
  }
</script>

<style lang="less" scoped>
  @base-color:#848686;
  .index-wrapper{
    width: 100%;
    height: 700px;
    background: salmon;
    overflow: hidden;
    .tab{
      /*position: relative;*/
      /*top: 100px;*/
      letter-spacing: 2px;
      display: flex;
      height: 20px;
      padding: 30px;
      border-bottom: 1px solid @base-color;
      .tab-item{
        flex: 1;
        align-items: center;
        a{
          display: block;
          text-align: center;
          line-height: 40px;
          font-size: 24px;
          font-weight: bold;
          color: @base-color;
          list-style: none;
          text-decoration: none;
        }
      }
    }
  }
</style>
