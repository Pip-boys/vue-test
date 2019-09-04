<template>
  <!--<el-card id="bar">
    <div>
      <el-row>
        <el-menu mode="horizontal" >
          <el-menu-item index="1" route="/">首页</el-menu-item>
          <el-menu-item index="2" style="margin-left: 2%" >留言板</el-menu-item>
          <el-menu-item index="3" style="margin-left: 2%" >本站公告</el-menu-item>
          <el-menu-item id="space" index="" class="hidden-xs-only"/>
          <div style="width: 20%;float: left;margin: 10px 2% 0px -5%" class="hidden-xs-only">
            <el-input placeholder="搜索博客" suffix-icon="el-icon-search"/>
          </div>

          <el-menu-item class="hidden-xs-only"  index="">
            <el-button type="text">登录</el-button>
          </el-menu-item>

          <el-menu-item class="hidden-xs-only" index="">
            <el-button type="text">注册</el-button>
          </el-menu-item>

          <el-dialog title="登录" width="21%">
            <el-form>
              <el-form-item >
                <el-input  placeholder="用户名" prefixIcon="el-icon-user-solid"/>
              </el-form-item>
              <el-form-item >
                <el-input placeholder="密码" prefixIcon="el-icon-lock"/>
              </el-form-item>
              <el-button>登录&nbsp;&nbsp;<i class="el-icon-check"></i></el-button>
            </el-form>
          </el-dialog>
          <el-dialog title="注册" width="30%">
            <el-form>
              <el-form-item >
                <el-input placeholder="用户名" prefixIcon="el-icon-user-solid"/>
              </el-form-item>
              <el-form-item>
                <el-input placeholder="密码" prefixIcon="el-icon-lock"/>
              </el-form-item>

              <el-form-item >
                <el-input placeholder="确认密码" prefixIcon="el-icon-bell"/>
              </el-form-item>


              <el-form-item >
                <el-input placeholder="邀请码" prefixIcon="el-icon-s-promotion"/>
              </el-form-item>
              <el-form-item>
                <el-input placeholder="邮箱" prefixIcon="el-icon-message"/>
              </el-form-item>
              <el-form-item >
                <el-input placeholder="邮箱验证码" prefixIcon="el-icon-key"/>
              </el-form-item>
              <el-button>
                发送验证码&nbsp;&nbsp;
                <i class="el-icon-coffee-cup" />
                <i class="el-icon-loading"/>
              </el-button>
              <el-button >注册&nbsp;&nbsp;<i class="el-icon-check"></i></el-button>
            </el-form>
          </el-dialog>
        </el-menu>
      </el-row>

    </div>

  </el-card>-->
</template>

<script>
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
      Head
    }
  };
</script>

<style>
  #bar {
    margin-top: 60px;
    margin-bottom: 0px;
  }

  #space {
    margin: 0 21% 0 20%;
  }
</style>
