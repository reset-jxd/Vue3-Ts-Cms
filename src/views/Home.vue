<template>
  <div class="home">
    <h1>Hello {{ $store.state.name }}</h1>
    <el-button type="primary">哈哈哈哈</el-button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Home',
  components: {}
})
</script>
