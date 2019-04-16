<template>
  <div class="vit-header">
    <vit-logo />
    <vit-nav />
    <vit-user />
  </div>
</template>
<script>
import VitLogo from './logo.vue'
import VitNav from './nav.vue'
import VitUser from './user.vue'
export default {
  components: {
    VitLogo,
    VitNav,
    VitUser
  }
}
</script>
<style lang="scss" scoped>
@import './index.scss';
</style>
