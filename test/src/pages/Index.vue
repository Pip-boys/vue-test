<template>
  <div class="head_background">
    <Head></Head>
    <HeadNavigation></HeadNavigation>
  </div>
</template>

<script>
  import HeadNavigation from '../pages/HeadNavigation';
  import Head from './Head';

  export default {
    data() {
      const item = {
        date: '2016-05-02',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1518 弄'
      };
      return {
        /*tableData: Array(20).fill(item)*/
      }
    },
    components:{
      HeadNavigation,Head

    }
  };
</script>

<style scoped>
  .head_background{
    height: 300px;padding: 10px;background: url('../../static/picture/background/background_head_title.png');border-bottom: 1px solid #F00;
  }
</style>
