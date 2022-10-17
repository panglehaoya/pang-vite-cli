<template>
  <div>
    {{ count }}
    {{ text }}
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'HelloWorld',
  setup() {
    const count = ref(0)
    const text = ref('hello vue3')
    return { count, text }
  },
})
</script>
