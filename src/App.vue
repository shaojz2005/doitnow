<template>
  <div id="app">
    <AppHeader></AppHeader>
    <AddTask></AddTask>
    <TaskList></TaskList>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AddTask from './components/AddTask.vue'
import TaskList from './components/TaskList.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AddTask,
    TaskList
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
