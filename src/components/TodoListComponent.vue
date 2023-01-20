<template>
  <div>
    <h2>TODO LIST</h2>
    <q-list>
      <q-item clickable v-ripple v-for="todo in todoList" :key="todo">
        <q-item-section>
          <q-item-label>{{ todo.title }}</q-item-label>
          <q-item-label class="text-grey-5" caption>{{
            todo.description
          }}</q-item-label>
        </q-item-section>
      </q-item>
    </q-list>
  </div>
</template>

<script setup lang="ts">
const todoList = [
  {
    id: 1,
    title: 'Task 1',
    description: 'Task 1 Description',
  },
  {
    id: 2,
    title: 'Task 2',
    description: 'Task 2 Description',
  },
  {
    id: 3,
    title: 'Task 3',
    description: 'Task 3 Description',
  },
];
</script>
