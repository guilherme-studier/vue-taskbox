<template>
  <div id="app">
    <header>Minhas tarefas</header>
    <Task />
  </div>
</template>

<script>

import Task from '@/components/Task'

export default {
  name: 'App',
  components: {
    Task,
  }
  
}
</script>

<style scoped>
  header {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 80px;
    font-size: 40px;
    color: #fff;
  }
</style>
