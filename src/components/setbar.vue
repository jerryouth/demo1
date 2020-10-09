<template>
<div>

<el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect">
  
  <el-button size="big" plain="true" id="setting_icon"  icon="el-icon-s-tools" ></el-button>
</el-menu>
<div class="line"></div>

</div>
</template>

<script>
  export default {
    data() {
      return {
        activeIndex: '1',
        activeIndex2: '1'
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>

<style scoped>
#setting_icon{
    float: right;
    margin-top: 10px;
    margin-right: 10px;
    margin-bottom: 10px;
    font-size: 22px;
    padding-left: 12px;
    padding-right: 12px;
    
}
</style>