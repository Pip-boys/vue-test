<template>
    <el-link href="https://element.eleme.io" target="_blank" :style="paddingbottom+'float: right;padding-left: 1%;'">
      <slot name="icon"></slot>
      <span style="font-size: 14px;color: #e2e2e2;">{{msg}}
        <span style="color: #e2e2e2;color: rgb(88, 62, 62);font-size: 16px;vertical-align: top;" v-if="flag==true">|</span>
      </span>
    </el-link>
</template>

<script>
export default {
  name: '',
  props:{
    msg:{
      default:'链接'
    },
    flag:{
      default:true
    },
    paddingbottom:{
      default: "padding-bottom: 2px;float: right;"
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
