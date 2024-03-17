<script setup>
import { ElMessage } from 'element-plus'
import { ref } from 'vue'

const name = ref('hyram')

const onClickSayHello = () => {
  ElMessage({ message: `hello ${name.value}`, type: 'success' })
}
</script>

<template>
  <h1>这里是首页</h1>
  <el-input v-model="name"></el-input>
  <el-button type="success" @click="onClickSayHello">Say Hello</el-button>
</template>
