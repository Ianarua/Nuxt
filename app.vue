<template>
    <NuxtLink to="/">首页</NuxtLink>
    <br>
    <NuxtLink to="/video">视频页</NuxtLink>
    <van-button type="primary">主要按钮</van-button>
    <NuxtPage/>
</template>
<script setup lang="ts">
useSeoMeta({
    title: 'bilibili',
    description: '视频网站',
});
</script>
<style>
:root {
    --van-primary-color: #FB7299 !important;
}
</style>