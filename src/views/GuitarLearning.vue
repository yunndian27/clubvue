<template lang='pug'>
#gauitar
  h1 教學內容
  router-link(to='/') 回社團首頁
  router-link(to='/guitar') 吉他社社史
  router-link(to='/guitar/event') 近期活動公告
</template>

<script>
export default {
  name: 'Guitar'
}
</script>
