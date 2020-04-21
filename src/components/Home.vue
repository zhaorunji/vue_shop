<template>
    <el-button type='info' @click="loginOut">退出</el-button>
</template>
<script>
export default {
  methods: {
    loginOut() {
      window.sessionStorage.clear()
      this.$router.push('/login')
    }
  }
}
</script>
<style scoped>

</style>
