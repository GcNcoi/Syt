<template>
  <div>
    <!-- 轮播图 -->
    <Carousel />
    <!-- 首页搜索医院 -->
    <Search />
  </div>
</template>
<script setup lang="ts">
import Carousel from "./carousel/index.vue";
import Search from "./search/index.vue";
</script>
<style scoped>
.hospital {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
</style>