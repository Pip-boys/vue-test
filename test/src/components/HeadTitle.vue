<template>
    <el-link href="https://element.eleme.io" target="_blank" style="padding-bottom: 2px;">
      <slot name="icon"></slot>
      <span style="font-size: 16px">{{msg}}</span>
    </el-link>
</template>

<script>
export default {
  name: '',
  props:{
    msg:{
      default:'链接'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
