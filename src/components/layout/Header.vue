<template>
  <el-header>
    <div class="logo"></div>
    <div class="text">
      SOSNicaragua {{ header? '| '+header:'' }}
    </div>
  </el-header>
</template>

<script>
export default {
  name: 'app-header',
  props: {
    header: String
  }
}
</script>

<style lang="scss">
.el-header {
  background: #409eff;

  padding: 3px;
  line-height: 3;
  color: white;
}
</style>
