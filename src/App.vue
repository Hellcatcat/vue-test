<template>
  <div id="app">
    <!-- <i class="el-icon-edit"></i>
    <i class="el-icon-share"></i>
    <i class="el-icon-delete"></i>
    <el-button type="primary" icon="el-icon-search">搜索</el-button> -->
    <!-- 路由出口 -->
    <!-- 路由匹配到的组件将渲染在这里 -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>
<style lang="less">
html,body,h3,p {
  margin: 0;
  padding: 0;
}
</style>
