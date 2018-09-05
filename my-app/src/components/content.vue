<template>
      <el-main>
        <el-breadcrumb separator-class="el-icon-arrow-right">
          <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
          <el-breadcrumb-item ><a href="/">客户信息管理</a></el-breadcrumb-item>
          <el-breadcrumb-item><a href="/">财务管理</a></el-breadcrumb-item>
          <el-breadcrumb-item><a href="/">处理流程管理</a></el-breadcrumb-item>
        </el-breadcrumb>
        <el-table :data="tableData" stripe=true border=true height="757">
                <el-table-column 
                  prop="name" 
                  label="公司名称" 
                  width="220">
                </el-table-column>
                <el-table-column 
                  prop="contacts" 
                  label="联系人" 
                  width="80">
                </el-table-column>
                <el-table-column 
                  prop="phone" 
                  label="联系电话" 
                  width="120">
                </el-table-column>
                <el-table-column 
                  prop="credit_code" 
                  label=" 统一信用代码"
                  width="200">
                </el-table-column>
                <el-table-column 
                  prop="national_code" 
                  label="国税密码" 
                  width="100">
                </el-table-column>
                <el-table-column 
                  prop="local_code" 
                  label="地税密码" 
                  width="100">
                </el-table-column>
                <el-table-column 
                  prop="net_code" 
                  label="网申码" 
                  width="80">
                </el-table-column>
                <el-table-column 
                  prop="corporate_representative" 
                  label="法人代表" 
                  width="80">
                </el-table-column>
                <el-table-column 
                  prop="id_card" 
                  label="身份证" 
                  width="180">
                </el-table-column>
                <el-table-column 
                  prop="address" 
                  label="地址" 
                  width="230">
                </el-table-column>
                <el-table-column 
                  prop="business_type" 
                  label="业务类型" 
                  width="150">
                </el-table-column> 
        </el-table>
      </el-main>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Content",
  data() {
      const item = {
        name: '深圳市海程国际贸易有限公司',
        contacts: '王小虎',
        phone: "13477581401",
        credit_code:"91440300MA5DHYT08T",
        national_code:"10042968",
        local_code:"a20170308",
        net_code:"431230",
        corporate_representative:"粟江南",
        id_card:"431230198503013011",
        address: '上海市普陀区金沙江路 1518 弄',
        business_type:"代理记帐和地址托管"
      }
      return {tableData: Array(20).fill(item)}
    }
}
</script>
<style scoped lang="scss">
  .el-main{
    .el-breadcrunb{
      margin-bottom: 60px;
    }
  }
</style>