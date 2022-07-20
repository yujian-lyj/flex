<template>
<div>
  <div class="box">
    <div class="panel">

        <el-card class="box-card">
          <div>1111111111</div>
             <img src="../img/编组.png" alt="" class="bianzu">
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
            margin:20px auto;
            display: flex;
            flex-flow: row wrap;
            /* justify-content: center;
             */
             justify-content:space-between;
            align-items: center;
        }
        .box .panel{
            flex: 0 0 50%;
            width: 30px;
            margin-bottom: 10px;
            margin-top: 10px;
        }
        .box-card{
          width: 395px;
          height: 200px;
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
        .four{
          margin-left: -70px;
          text-align: center;
          /* width: 100px; */
          padding: 10px 60px;
        }
        .h4{
          margin-left: -80px;
        }
        .bianzu{
          width: 50px;
          height: 50px;
          margin: 50px auto;
          float: right;
        }
</style>
