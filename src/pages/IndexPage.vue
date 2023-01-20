<template>
  <q-page class="row items-center justify-evenly">
    <TodoListComponent></TodoListComponent>
    <NewTodoComponent></NewTodoComponent>
  </q-page>
</template>

<script setup lang="ts">
import TodoListComponent from 'src/components/TodoListComponent.vue';
import NewTodoComponent from 'src/components/NewTodoComponent.vue';
</script>
