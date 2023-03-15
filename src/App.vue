<script setup>
import {RouterView} from 'vue-router'
import Header from "@/components/Header.vue";
</script>

<template>
  <div class="container">
    <Header></Header>
    <el-main>
      <RouterView/>
    </el-main>
  </div>
</template>

<style scoped>
.el-main {
  padding: 0 !important;
  font-family: PingFang SC-Medium, PingFang SC;
}
.el-main::-webkit-scrollbar{
  display:none
}
.container {
  min-width: 1500px;
}
</style>
