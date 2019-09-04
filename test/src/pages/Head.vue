<template>
  <div>
    <el-row>
      <el-col :span="24">
        <div class="grid-content bg-purple-dark" style="padding: 15px 30px 0px 2%;background: #578ae8;">
          <table>
            <tr>
              <td>
                <img src="../../static/icon/red_triangle.png" style="float: left;height: 15px;margin-right: 6px;">
                <span style="font-size: 16px;float: left;color: #f9fafc">BIBIBOY.COM</span>
              </td>
              <td>
                <HeadTitle msg="手机客户端">
                  <img slot="icon" src="../../static/icon/phone.png" style="vertical-align: sub;height: 22px;"/>
                </HeadTitle>
                <HeadTitle msg="哔哔商城">

                </HeadTitle>
              </td>
            </tr>
          </table>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
  import HeadTitle from '../components/HeadTitle';

  export default {
    data() {
      const item = {

      };
      return {
        /*tableData: Array(20).fill(item)*/
      }
    },
    components:{
      HeadTitle
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
