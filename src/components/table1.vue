<template>
  <el-table
    :data="tableData"
    style="width: 100%"
    >
    <el-table-column
      fixed
      
      prop="date"
      label="单号"
      width="200">
    </el-table-column>
    <el-table-column
      
      prop="name"
      label="标题"
      width="150">
      
    </el-table-column>
    <el-table-column
      prop="province"
      label="服务目录"
      width="160">
    </el-table-column>
    <el-table-column
      prop="city"
      label="类型"
      width="120">
    </el-table-column>
    <el-table-column
      prop="address"
      label="优先级"
      width="120">
    </el-table-column>
    <el-table-column
      prop="zip"
      label="提单人"
      width="120">
    </el-table-column>
        <el-table-column
      prop="time"
      label="提单时间"
      width="180">
    </el-table-column>
    <el-table-column
      prop="situation"
      label="状态"
      width="100">
    </el-table-column>
    <el-table-column
      
      width="100">
    </el-table-column>
        <el-table-column
      
      width="90">
    </el-table-column>
  </el-table>
</template>
<style>
  .warning-row {
    background: red;
  }

  .el-table .success-row {
    background: #FFF;
  }
</style>
<script>
  export default {
    methods: {
      handleClick(row) {
        console.log(row);
      }
    },

    data() {
      return {
        tableData: [{
          date: 'REQ20191227000001',
          name: '文件申请测试-1',
          province: 'Kris>文件申请',
          city: '请求管理',
          address: '低',
          zip: 'kris',
          time: '2019-12-27 16:52:49',
          situation: '处理中'
        }, {
          date: 'REQ20191227000001',
          name: '文件申请测试-1',
          province: 'Kris>文件申请',
          city: '请求管理',
          address: '低',
          zip: 'kris',
          time: '2019-12-27 16:52:49',
          situation: '处理中'
        },]
      }
    },
  }
</script>