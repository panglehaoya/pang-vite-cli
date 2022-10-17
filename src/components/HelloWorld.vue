<template>
  <div>
    {{ count1 }}
    {{ text }}
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'HelloWorld',
  setup() {
    const count1 = ref(0)
    const text = ref('hello vue3')
    return { count1, text }
  },
})
</script>
