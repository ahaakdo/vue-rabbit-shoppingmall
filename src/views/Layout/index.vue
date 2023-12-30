<script setup>
import layoutNav from './components/layoutNav.vue'
import layoutHeader from './components/layoutHeader.vue'
import layoutFooter from './components/layoutFooter.vue'
</script>
<template>
    <layoutNav></layoutNav>
    <layoutHeader></layoutHeader>
    <!-- 二级路由出口 -->
    <router-view></router-view>
    <layoutFooter></layoutFooter>
</template>
<style>
    div{
        color: rgb(30, 131, 225);
    }
</style>