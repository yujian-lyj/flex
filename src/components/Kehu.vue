<template>
<div>
  <div class="box">
       <div class="panel three">
        <div class="item "><h3 class="h4">典型客户</h3></div>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
        <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
     <div class="panel">
        <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
     <div class="panel">
        <el-card class="box-card">

             <img src="../img/北大科技园005.png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
            </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
            </el-card>
    </div>
        <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
            </el-card>
    </div>
        <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
            </el-card>
    </div>
        <div class="panel">
             <el-card class="box-card">

              <img src="../img/北大科技园005.png" alt="" class="bianzu">
            </el-card>
    </div>
</div>
     <div class="four">
        <div class="tag-group"><el-tag type='info'>更多客户案例</el-tag></div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
   .box{
            position: relative;
            width:700px;
            margin:0 auto;
            display: flex;
            flex-flow: row wrap;
            justify-content: center;
            align-items: center;
        }
        .box .panel{
            flex: 0 0 16.66666%;
            width: 50px;
            margin-bottom: 10px;
            margin-top: 10px;
        }
        .box-card{
          width: 80px;
          height: 80px;
        }
        .box .panel .item{
            display: block;
            text-align: center;
            margin:10px 10px;
            height: 30px;
        }
        .box .panel.three{
            flex:0 0 100%;
            /* margin-top: -10px; */
        }
        .h4{
          margin-left: -30px;
        }
        .bianzu{
          width: 100px;
          height: 100px;
          margin: -30px -30px;
          /* float: right; */
        }
        .four{
          margin-left: -70px;
          text-align: center;
          /* width: 100px; */
          padding: 10px 60px;
        }
</style>
