<template>
  <div class='components-wrap'>
      <Datetime/>
      <TikTokDownloadResult/>
  </div>
</template>

<script>
import Datetime from '@/components/Datetime.vue'
import TikTokDownloadResult from '@/components/TikTokDownloadResult.vue'

export default {
  components: {
    Datetime,
    TikTokDownloadResult
  }
}
</script>

<style>
.components-wrap{
  display:flex;
  flex-wrap:wrap;
  font-family:"pointy"
}
.components-wrap>div{
  margin:10px
}
</style>