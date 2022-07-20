<template>
<div class="all">
<el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect">
   <el-menu-item  index='0'>
    <img src="../img/新版logo.png" alt="" class="logo">
   </el-menu-item>
  <el-menu-item index="1">首页</el-menu-item>
  <el-submenu index="2">
    <template slot="title">预算解决方案</template>
    <el-menu-item index="2-1">选项1</el-menu-item>
    <el-menu-item index="2-2">选项2</el-menu-item>
    <el-menu-item index="2-3">选项3</el-menu-item>
  </el-submenu>
  <el-submenu index="3">
      <template slot="title">软件产品</template>
      <el-menu-item index="3-1">选项1</el-menu-item>
      <el-menu-item index="3-2">选项2</el-menu-item>
      <el-menu-item index="3-3">选项3</el-menu-item>
  </el-submenu>
  <el-submenu index="4">
      <template slot="title">客户案例</template>
      <el-menu-item index="3-1">选项1</el-menu-item>
      <el-menu-item index="3-2">选项2</el-menu-item>
      <el-menu-item index="3-3">选项3</el-menu-item>
  </el-submenu>
   <el-menu-item index="5" >行业前沿</el-menu-item>
  <el-submenu index="6">
      <template slot="title">关于我们</template>
      <el-menu-item index="3-1">选项1</el-menu-item>
      <el-menu-item index="3-2">选项2</el-menu-item>
      <el-menu-item index="3-3">选项3</el-menu-item>
  </el-submenu>
 <div index="7" class="phone">
    <img src="../img/电话.png" alt="">
    <span>
    400-818-6860
    </span>
  </div>
</el-menu>
</div>
</template>

<script>
export default {
         data() {
      return {
        activeIndex: '1',
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
.all{
  position: relative;
  background: #fff;
}
.logo{
  width: 60px;
  height: 50px;
  margin: 0 auto;
  padding-right: 100px;
}
.el-menu-demo{
  height: 65px;
  width: 100%;
}
.phone{
  width:200px ;
  height: 100px;
  float: right;
  padding-top: 15px;
}
</style>>


