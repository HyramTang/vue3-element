<template>
  <div class="common-layout">
    <el-container>
      <el-header>Header</el-header>
      <el-main class="no-padding">
        <el-row justify="center">
          <router-view></router-view>
        </el-row>
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>
