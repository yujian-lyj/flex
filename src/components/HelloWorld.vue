<template>
<div class="b">
  <top></top>
  <heads></heads>
  <text1></text1>
  <fangan></fangan>
  <yusuan></yusuan>
  <siyou></siyou>
  <feilong></feilong>
  <kehu></kehu>
  <bottom></bottom>
</div>
</template>

<script>
import top from './Top.vue';
import heads from './Head.vue';
import fangan from './Fangan.vue';
import text1 from './text.vue';
import yusuan from './Yusuan.vue';
import siyou from './Siyou.vue';
import feilong from './Feilong.vue';
import kehu from './Kehu.vue';
import bottom from './Bottom.vue';
export default {
  name: 'HelloWorld',
  components: {
    top: top,
    heads: heads,
    fangan: fangan,
    text1: text1,
    yusuan: yusuan,
    siyou: siyou,
    feilong: feilong,
    kehu: kehu,
    bottom: bottom
  },
  data () {
    return {

    }
  }
}
</script>

<style scoped>

</style>
