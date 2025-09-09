<template>
  <div class="search">
    <el-autocomplete clearable placeholder="请输入医院名称" />
    <el-button type="primary" size="default" :icon="Search">搜索</el-button>
  </div>
</template>
<script setup lang="ts">
import { Search } from "@element-plus/icons-vue";
</script>
<style scoped lang="scss">
.search {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 50%;
  height: 50px;
  margin-top: 10px 0px;
  ::v-deep(.el-input__wrapper) {
    width: 600px;
    margin-right: 10px;
  }
}
</style>