<template>
  <div style="height: 200px;">
    <el-row style="box-shadow: #406dbf 2px 8px 20px -2px;">
      <el-col :span="24">
        <div class="grid-content bg-purple-dark" style="padding: 15px 30px 0px 2%;background: rgba(101, 145, 224, 0.8);">
          <table>
            <tr>
              <td style="width: 10%;">
                <img src="../../static/picture/icon/red_triangle.png" style="float: left;height: 15px;margin-right: 6px;">
                <span style="font-size: 16px;float: left;color: #f9fafc">BIBIBOY.COM</span>
              </td>
              <td style="width: 10%;">
                <HeadTitle msg="注册" flag="false">
                </HeadTitle>
                <HeadTitle msg="登陆" flag="false">
                  <img slot="icon" src="../../static/picture/icon/person_unlogin.png" style="vertical-align: sub;height: 18px;"/>
                </HeadTitle>

                <HeadTitle msg="通知" paddingbottom="">
                </HeadTitle>
                <HeadTitle msg="热点新闻" paddingbottom="">
                </HeadTitle>
                <HeadTitle msg="网站导航" paddingbottom="">
                </HeadTitle>
                <HeadTitle msg="哔哔商城" paddingbottom="">
                </HeadTitle>
                <HeadTitle msg="手机客户端">
                  <img slot="icon" src="../../static/picture/icon/phone.png" style="vertical-align: sub;height: 18px;"/>
                </HeadTitle>
              </td>
            </tr>
          </table>
        </div>
      </el-col>
    </el-row>

    <div>
      <Title></Title>
    </div>
    <div>

    </div>
  </div>
</template>

<script>
  import HeadTitle from '../components/HeadTitle';
  import Title from '../components/Title';
  export default {
    name:'',
    data() {
      const item = {

      };
      return {
        /*tableData: Array(20).fill(item)*/
      }
    },
    components:{
      HeadTitle,Title
    }
  };
</script>

<style scoped>

  .el-row {
    margin-bottom: 20px;
  &:last-child {
     margin-bottom: 0;
   }
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>
