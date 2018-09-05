<template>
  <div id="app">
      <Header></Header>
      <Aside>
      </Aside>
  </div>
</template>

<script>
import Header from './components/header.vue'
import Aside from './components/aside.vue'
import Content from './components/content.vue'

export default {
  name: 'app',
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
