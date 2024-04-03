<template>
  <input type="text" placeholder="添加任务至“收集箱”，回车即可保存">
</template>

<script>
export default {
  name: 'AddTask',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
  input{
    background-color: rgba(25, 25, 25, 0.03);
    border: none;
    padding: 15px;
    border-radius: 5px;
  }
</style>
