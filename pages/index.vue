<template>
  <div class="home">
    <div wh-200 bg-blue font-600 color-red flexc>小滴课堂</div>
    <a-button type="primary" bg-green! color-red>按钮</a-button><br />
    <h1>当前pinia的初始化值{{ count }}</h1>
    <h2 @click="addClick">增加</h2>
    <h2>当前pinia的计算的值：{{ multiplyCount }}</h2>
  </div>
</template>

<script lang="ts" setup>
const { count, add, multiplyCount } = $(useUser())
const addClick = () => add()
</script>

<style lang="scss" scoped></style>
