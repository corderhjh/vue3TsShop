<template>
  <div class="">登录</div>
  <div>{{ $store.state.name }}</div>
</template>

<script lang="ts">
//这里使用的ts
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'login',
  setup() {
    //这里存放数据
    return {}
  }
})
</script>
<style lang="less" scoped>
//@import url()
</style>
