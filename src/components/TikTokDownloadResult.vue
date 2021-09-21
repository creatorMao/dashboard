<template>
    <div class='TikTokDownloadResult'>
       <wired-listbox id="combo">
            <wired-item value="one">下载视频:63个</wired-item>
            <wired-item value="two">下载图片:0张</wired-item>
            <wired-item value="three">耗时:9.4分钟</wired-item>
            <wired-item value="three">日期:2021-09-21 11:48:32</wired-item>
        </wired-listbox>
    </div>
</template>

<script>
import "wired-elements";

export default {
    props:{
        date:{
            default:'2021-09-19'
        }
    },
}
</script>

<style>
.TikTokDownloadResult{
    font-size:30px;
}
.date{
    font-size:44px;
}
.time{
  font-size:30px;  
  text-align:center;
}
</style>