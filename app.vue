<template>
  <NuxtLayout>
    <div>
      <van-button type="primary">Primary</van-button>
      <van-button type="success">Success</van-button>
      <van-button type="default">Default</van-button>
      <van-button type="danger">Danger</van-button>
      <van-button type="warning">Warning</van-button>
      {{ x }} - {{ y }}
    </div>
  </NuxtLayout>
</template>

<script setup lang="ts">
const { x, y } = useMouse()
</script>