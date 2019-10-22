<template>
  <div class="home">
    <div class="container">
      <AddTodo />
      <FilterTodos />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from '@/components/Todos.vue';
import AddTodo from '@/components/AddTodo.vue';
import FilterTodos from '@/components/FilterTodos.vue';

export default {
  name: 'home',
  components: {
    Todos,
    AddTodo,
    FilterTodos
  }
};
</script>
