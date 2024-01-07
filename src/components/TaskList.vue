<template>
  <header>
    任务列表
    <TaskItem></TaskItem>
  </header>
</template>

<script>
import TaskItem from './TaskItem.vue'
export default {
  name: 'TaskList',
  components: {
    TaskItem
  },
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
