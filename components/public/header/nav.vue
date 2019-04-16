<template>
  <el-menu
    :default-active="activeIndex"
    class="vit-header-nav"
    mode="horizontal"
    @select="handleSelect"
  >
    <el-menu-item index="1">首页</el-menu-item>
    <el-menu-item index="2">文章分类</el-menu-item>
    <el-menu-item index="3">标签</el-menu-item>
    <el-menu-item index="4">文章归档</el-menu-item>
    <el-menu-item index="5">日志</el-menu-item>
    <el-menu-item index="6">留言板</el-menu-item>
  </el-menu>
</template>
<script>
export default {
  data() {
    return {
      activeIndex: '1'
    }
  },
  methods: {
    handleSelect() {}
  }
}
</script>
<style lang="scss" scoped></style>
