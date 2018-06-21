<template>
  <div id="app">
    <my-head></my-head>
      <index></index>
      <router-view></router-view>
    <my-footer></my-footer>
  </div>
</template>

<script>
  import MyHead from './components/MyHead/MyHead'
  import MyFooter from './components/MyFoot/MyFoot'
  import Index from './view/Index'

  export default {
    name: 'App',
    components: {
      MyHead,
      MyFooter,
      Index
    }
  }
</script>

<style lang="less">

</style>
