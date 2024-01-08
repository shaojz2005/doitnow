<template>
  <div id="sidebar">
    侧边栏
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
  props: {
  }
}
</script>

<style lang="less" scoped>
  #sidebar{
    background-color: rgba(71, 114, 250, 0.8);
    color: #fff;
    width: 50px;
    padding: 10px 5px;
    flex-shrink: 0;
  }
</style>
