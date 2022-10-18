<!-- 使用 el-icon 为 SVG 图标提供属性 -->
<template>
  <div>
    <el-icon :size="20" color="#409EFC">
      <Edit />
    </el-icon>
    <!-- 或者独立使用它，不从父级获取属性 -->
    <Edit />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IconVue',
})
</script>
