<template>
  <div>
    <el-button>{{msg}}</el-button>
  </div>
</template>

<script>

export default {
  name: '',
  props: {
    msg: {
      default: '默认值'
    }
  },
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  div{
    font-family: cursive;
    font-size: x-large;
  }
</style>
