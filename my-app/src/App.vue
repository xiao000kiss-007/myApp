<template>
  <div id="app">
      <Header></Header>
      <Aside>
      </Aside>
      <Content>
      </Content>
  </div>
</template>

<script>
import Header from './components/header.vue'
import Aside from './components/aside.vue'
import Content from './components/content.vue'

export default {
  name: 'app',
  data() {
      const item = {
        date: '2016-05-02',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1518 弄'
      };
      return {
        tableData: Array(20).fill(item)
      }
    },
  
  components: {
    Header,
    Aside,
    Content
  }
}
</script>

<style scoped lang="scss">

#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  list-style: none;
  text-decoration: none;
  }
</style>
