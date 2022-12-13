<template>
  <div @click="handleClick">首页</div>
  <h1>{{ xd }}</h1>
  <a-button type="primary">按钮</a-button>
</template>

<script setup>
const xd = $ref(1)

const handleClick = () => {
  xd++
}
</script>

<style lang="scss" scoped></style>
