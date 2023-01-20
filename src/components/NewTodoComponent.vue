<template>
  <div>
    <h2>New TODO</h2>
    <q-input v-model="title" label="Title"></q-input>
    <q-input v-model="description" label="Description" type="textarea"></q-input>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const title = ref('');
const description = ref('');
</script>
