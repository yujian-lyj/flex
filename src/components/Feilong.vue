<template>
<div>
  <div class="box">
       <div class="panel three">
        <div class="item "><h4 class="h4">为什么选择融智天·飞龙</h4></div>
    </div>
    <div class="panel">
             <el-card class="box-card">
              <div>1111111111</div>
              <img src="../img/编组(2).png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
                <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
               <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
               <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
        <el-card class="box-card">
               <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
     <div class="panel">
        <el-card class="box-card">
               <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
     <div class="panel">
        <el-card class="box-card">
               <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
              <div>1111111111</div>
              <img src="../img/编组(1).png" alt="" class="bianzu">
            </el-card>
    </div>

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
            width:800px;
            margin:0 auto;
            display: flex;
            flex-flow: row wrap;
            justify-content: center;
            align-items: center;
        }
        .box .panel{
            flex: 0 0 25%;
            width: 50px;
            margin-bottom: 10px;
            margin-top: 10px;
        }
        .box-card{
          width: 150px;
          height: 70px;
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
          margin-left: -80px;
        }
        .bianzu{
          width: 20px;
          height: 20px;
          margin: -30px -12px;
          float: right;
        }
</style>
