<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <v-btn type="button" @click="count++">count is {{ count }}</v-btn>
  </div>
</template>

<style scoped>
</style>
