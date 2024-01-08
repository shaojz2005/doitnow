<template>
  <div id="app">
    <Sidebar></Sidebar>
    <Category></Category>
    <TaskList></TaskList>
    <TaskDetail></TaskDetail>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Category from './components/Category.vue'
import TaskList from './components/TaskList.vue'
import TaskDetail from './components/TaskDetail.vue'

export default {
  name: 'App',
  components: {
    TaskList,
    Sidebar,
    Category,
    TaskDetail
  }
}
</script>

<style lang="less">
#app {
  height: 100%;
  display: flex;
  align-items: stretch;
}

</style>
