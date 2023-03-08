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
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<style scoped>
.el-main {
  padding: 0 !important;
}

.el-container {
  height: 100vh;
  width: 100vw;
}
</style>
