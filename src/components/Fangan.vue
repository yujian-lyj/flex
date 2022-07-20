<template>
<div>
  <div class="box">
       <div class="panel three">
        <div class="item "><h4 class="h4">费用管理解决方案</h4></div>
    </div>
    <div class="panel">
             <el-card class="box-card">
  <div v-for="o in 1" :key="o" class="text item">
    {{'列表内容 ' + o }}
  </div>
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
  <div v-for="o in 1" :key="o" class="text item">
    {{'列表内容 ' + o }}
  </div>
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
  <div v-for="o in 1" :key="o" class="text item">
    {{'列表内容 ' + o }}
  </div>
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
  <div v-for="o in 1" :key="o" class="text item">
    {{'列表内容 ' + o }}
  </div>
      </el-card>
    </div>
    <div class="panel">
        <el-card class="box-card">
             <div v-for="o in 1" :key="o" class="text item">
               {{'列表内容 ' + o }}
             </div>
      </el-card>
    </div>
    <div class="panel">
             <el-card class="box-card">
               <div v-for="o in 1" :key="o" class="text item">
                {{'列表内容 ' + o }}
              </div>
            </el-card>
    </div>

</div>
     <div class="four">
        <div class="tag-group"><el-tag type='info'>了解更多</el-tag></div>
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
            /* justify-content: center;
             */
             justify-content:space-between;
            align-items: center;
        }
        .box .panel{
            flex: 0 0 16.6666%;
            width: 30px;
            margin-bottom: 10px;
            margin-top: 10px;
        }
        .box-card{
          width: 100px;
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
</style>
