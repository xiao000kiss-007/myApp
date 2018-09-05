<template>
    <div class="myHeader">
      <el-container>
        <el-header >
        <div class="logo">
            <h3>深圳市恒深财务CRM管理系统</h3>
            <p>v1.0.0</p>
        </div>
        <el-button type="primary" icon="el-icon-search" style="margin-right: 15px">搜索</el-button>
        <i class="el-icon-edit" style="margin-right: 15px"></i>
        <i class="el-icon-share" style="margin-right: 15px"></i>
        <i class="el-icon-delete" style="margin-right: 15px"></i>
        <el-dropdown size="100px">
            <span>
                设置<i class="el-icon-setting" style="margin-right: 15px"></i>
            </span>
            <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>查看</el-dropdown-item>
            <el-dropdown-item>新增</el-dropdown-item>
            <el-dropdown-item>删除</el-dropdown-item>
        </el-dropdown-menu>
        </el-dropdown>
        </el-header>
      </el-container>
    </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Header"
};
</script>

<style scoped lang="scss">
.myHeader{
       .el-container {
           height: 60px;
           border: 1px solid #eee;
            .el-header {
                height: 60px;
                background-color: #409EFF;
                color: #333;
                line-height: 60px;
                text-align: right;
                font-size: 24px;

        }
    }
    .logo{
        height: 60px;
        line-height: 60px;
        margin-top: 5px;
        float: left;
        background: url("../assets/logo2.png") no-repeat;
        h3{
            display: block;
            float: left;
            margin-left:60px;
            color: #eee;
        }
        p{
            display: block;
            float: left;
            line-height: 80px;
            font-size: 16px;
            color: rgb(173, 6, 6);
        }
    }
}
</style>