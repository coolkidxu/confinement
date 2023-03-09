<script setup>
import {ref} from 'vue'

const activeIndex = ref('1')
const handleSelect = (key, keyPath) => {
  console.log(key, keyPath)
}
</script>

<template>
  <div class="header-container">
    <div class="menu-container">
      <div class="logo"></div>
      <el-menu
          :default-active="activeIndex"
          mode="horizontal"
          @select="handleSelect"
      >
        <el-menu-item index="1">首页</el-menu-item>
        <el-menu-item index="2">了解套餐</el-menu-item>
        <el-menu-item index="3">服务礼遇</el-menu-item>
        <el-menu-item index="4">真实口碑</el-menu-item>
        <el-menu-item index="5">预约服务</el-menu-item>
        <el-menu-item index="6">月子百科</el-menu-item>
        <el-menu-item index="7">关于我们</el-menu-item>
        <el-menu-item index="8">真实口碑</el-menu-item>
      </el-menu>
      <div class="contact">月子咨询 0316-6554666</div>
    </div>
  </div>
</template>
<style>
.header-container {
  background-color: var(--el-color-primary);
  text-align: center;
  height: 110px;
  padding-top: 30px;
}
.menu-container {
  width: 100%;
  background-color: white;
  display: flex;
  justify-content: space-around;
  gap: 2em;
  align-items: center;
}
.logo,.contact {
  flex-grow: 1;
}
.logo {
  width: 3em;
  height: 3em;
  background: url("@/assets/zcinfo.svg") no-repeat;
  background-size: 100% 100%;
}
.el-menu {
  flex-grow: 2;
  display: flex;
  justify-content: center;
}

</style>
