<template>
<div>
    <el-menu :default-active="activeIndex" id="pagination" class="el-menu-demo" mode="horizontal" @select="handleSelect">
        <div class="block">
            <el-pagination
                @size-change="handleSizeChange"
                @current-change="handleCurrentChange"
                :current-page.sync="currentPage2"
                :page-sizes="[5, 10, 15 , 20]"
                :page-size="5"
                layout="total,sizes, prev, pager, next"
                :total="1000">
            </el-pagination>
        </div>
    </el-menu>
    <div class="line"></div>
</div>
</template>
<style scoped>
#pagination{
    height: 30px;
    padding-top: 10px;
    padding-bottom: 10px;
}
</style>
<script>
  export default {
    methods: {
      handleSizeChange(val) {
        console.log(`每页 ${val} 条`);
      },
      handleCurrentChange(val) {
        console.log(`当前页: ${val}`);
      }
    },
    data() {
      return {
        currentPage1: 5,
        currentPage2: 5,
        currentPage3: 5,
        currentPage4: 4
      };
    }
  }
</script>