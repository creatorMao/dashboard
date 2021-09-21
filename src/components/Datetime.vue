<template>
    <div>
         <wired-card elevation="1">
            <div class='date'>{{date}}</div>
            <div class='time'>{{"12:27:20"}}</div>
        </wired-card>
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
.date{
    font-size:44px;
}
.time{
  font-size:30px;  
  text-align:center;
}
</style>