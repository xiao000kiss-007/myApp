<template>
    <div class="myHeader">
      <el-container>
        <el-header >
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
}
</style>