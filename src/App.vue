<script setup>
import {RouterView} from 'vue-router'
import Header from "@/components/Header.vue";
</script>

<template>
  <el-container>
    <Header></Header>
    <el-main>
      <RouterView/>
    </el-main>
  </el-container>
</template>

<style scoped>
.el-main {
  padding: 0 !important;
  font-family: PingFang SC-Medium, PingFang SC;
}
.el-main::-webkit-scrollbar{
  display:none
}

.el-container {
  height: 100vh;
  min-width: 1500px;
}
</style>
