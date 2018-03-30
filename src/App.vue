<template>
  <div id="app">
    <heade></heade>
    <div class="banner">banner图</div>
    <div class="listNave">列表搜索</div>
    <div class="hotArea">热门地区</div>
    <div class="roll">团</div>
    <div class="footer">底部</div>
  </div>
</template>

<script>
import header from './components/hrader/header.vue';
export default {
  components:{
    heade:header
  }
}
</script>

<style>
</style>
