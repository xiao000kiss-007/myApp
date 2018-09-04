<template>
  <div class="home">
    <el-row>
        <h1>欢迎来到KAdmin管理系统v1.0.0</h1>
        <el-button><router-link to="/">返回首页</router-link></el-button>
        <el-button type="primary" plain><router-link to="/about">关于我们</router-link></el-button>
    </el-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home"
};
</script>

<style scoped lang="scss">
  a {
  text-decoration: none;
  font-size: 14px;
  color: #000;
  }
</style>