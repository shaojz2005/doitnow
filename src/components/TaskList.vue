<template>
  <div id="task-list">
    <TaskHeader></TaskHeader>
    <AddTask></AddTask>
    任务列表
  </div>
</template>

<script>
import TaskHeader from './TaskHeader.vue'
import AddTask from './AddTask.vue'
export default {
  name: 'TaskList',
  components: {
    TaskHeader,
    AddTask
  },
  props: {
  }
}
</script>

<style lang="less" scoped>
  #task-list{
    flex-grow: 1;
    border-right: 1px solid rgba(25, 25, 25, 0.05);
    padding: 20px;
    display: flex;
    flex-direction: column;
  }
</style>
