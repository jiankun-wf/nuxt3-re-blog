<script setup lang="ts">
defineProps<{
  error: any;
}>();
</script>

<template>
  <div>错啦：{{ error }}</div>
</template>

<style lang="less" scoped></style>
