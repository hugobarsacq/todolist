<template>
  <div class="todolist">
    <ToDoList/>
  </div>
</template>

<script>
// @ is an alias to /src
import ToDoList from '@/components/ToDoList.vue';

export default {
  name: 'ToDoListView',
  components: {
    ToDoList,
  },
};
</script>

<style>
#todolist {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50; */
  color: #333;
  margin-top: 60px;
}
</style>
