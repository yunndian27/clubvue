<template lang="pug">
#update
  | 最後更新日期： {{ data }}
</template>

<script>
export default ({
  name: 'Update',
  data () {
    return {
      data: new Date().toLocaleString()
    }
  }
})
</script>
