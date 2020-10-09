<script src="//unpkg.com/vue/dist/vue.js"></script>
<script src="//unpkg.com/element-ui@2.13.2/lib/index.js"></script>

<template>
  <div id="header_box">
      <div id="request_manage" class="text_box">
          <a href="#">请求管理</a>
      </div>
      <div id="change_manage" class="text_box">
          <a href="#">变更管理</a>
      </div>
      <div class="text_box">
          <a href="#">事件管理</a>
      </div>
      <div class="text_box">
          <a href="#">问题管理</a>
      </div>
  </div>
      

  
  
</template>

<script>
export default {
  name: 'Header',
  data () { 
  },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#header_box{
    background-color:red;
    border-width: 0px;
    position: absolute;
    /* margin: auto; */
    
    top: 122px;
    width: 1111px;
    height: 52px;
    background: inherit;
    background-color: rgba(255, 255, 255, 1);
    box-sizing: border-box;
    border-width: 1px;
    border-style: solid;
    border-color: rgba(221, 222, 223, 1);
    border-radius: 0px;
    box-shadow: none;
}
a{
    text-decoration: none;
    color: #737987;
    font-family: 'PingFangSC-Regular', 'PingFang SC';
    font-weight: 400;
    font-style: normal;
    font-size: 14px;
    
}
a:hover{
   color: #3C96FF;
}
#request_manage{
    margin-left: 20px;
}
.text_box{
    /* position: absolute; */
    align-self: center;
    padding: 2px 12px 2px 12px;
    /* box-sizing: border-box; */
    width: 69px;
    height: 100%;
    float: left;
    line-height: 50px;
    /* background-color: sandybrown; */
}
</style>
