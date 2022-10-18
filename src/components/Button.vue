<script lang="tsx">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ButtonComponent',
  setup() {
    function handleClick() {
      console.log('click')
    }
    return () => {
      return <el-button onClick={handleClick}>点击</el-button>
    }
  },
})
</script>
