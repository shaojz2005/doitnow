<template>
  <div id="category">
    分类栏
  </div>
</template>

<script>
export default {
  name: 'Category',
  props: {
  }
}
</script>

<style lang="less" scoped>
  #category{
    background-color: rgb(242, 245, 254);
    border-right: 1px solid rgba(25, 25, 25, 0.05);
    width: 212px;
    flex-shrink: 0;
    padding: 10px;
  }
</style>
