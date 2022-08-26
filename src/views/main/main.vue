<template>
  <div class="">主页</div>
  <el-button>默认按钮</el-button>
  <el-button type="primary">主要按钮</el-button>
  <el-button type="success">成功按钮</el-button>
  <el-button type="info">信息按钮</el-button>
  <el-button type="warning">警告按钮</el-button>
  <el-button type="danger">危险按钮</el-button>
</template>

<script lang="ts">
//这里使用的ts
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'main',
  setup() {
    //这里存放数据
    return {}
  }
})
</script>
<style lang="less" scoped>
//@import url()
</style>
