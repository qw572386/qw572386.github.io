<template>
  <el-container>
    <el-header>
      <vit-header />
    </el-header>
    <el-main>
      <nuxt />
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>
<script>
import VitHeader from '~/components/public/header'
export default {
  components: {
    VitHeader
  }
}
</script>
<style></style>
