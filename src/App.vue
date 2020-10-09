<template>
  <div id="app">
  <el-container>
  <el-header><header3></header3></el-header>
  <el-main>
    <setbar></setbar>
    <table1></table1>
    <pagination></pagination>


  </el-main>
  </el-container>
    
  </div>
</template>

<script>
import header3 from './components/header3'
import setbar from './components/setbar'
import table1 from './components/table1'
import pagination from './components/pagination'
export default {
  name: 'App',
  components:{
    header3,
    setbar,
    table1,
    pagination
  },
}
</script>

<style>

</style>
