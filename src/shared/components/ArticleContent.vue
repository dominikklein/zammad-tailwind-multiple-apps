<script setup lang="ts">
defineProps<{ title: string; body: string }>()
</script>

<template>
  <h1>{{ title }}</h1>

  <div class="text-center">
    {{ body }}
  </div>
</template>

<style scoped></style>
