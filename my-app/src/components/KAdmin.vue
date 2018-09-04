<template>
    <div class="main">
      <p>后台管理系统</p>
        <el-button><router-link to="/">返回首页</router-link></el-button>
        <el-button type="primary" plain><router-link to="/about">关于我们</router-link></el-button>
    </div>
  </template>

<script>
export default {
  name: 'KAdmin',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped lang="scss">
    a{
    text-decoration: none;
    font-size: 14px;
    color: #000;
  }
</style>