<template>
  <div class="container">
    <HospitalTop />
    <div class="content">
      <router-view />
    </div>
    <HospitalBottom />
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped lang="scss">
.container {
  align-items: center;
  display: flex;
  flex-direction: column;
  .content {
    width: 1800px;
    min-height: 899px;
  }
}
</style>