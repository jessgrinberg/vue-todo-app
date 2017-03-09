<template>
  <div id="app">
    <todo-list v-bind:todos="todos"></todo-list>
  </div>
</template>

<script>
import TodoList from './components/TodoList'

export default {
  components: {
    TodoList
  }
}
</script>

<style>

</style>
