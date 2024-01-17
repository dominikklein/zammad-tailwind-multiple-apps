<script setup lang="ts">
import ArticleContent from '../../shared/components/ArticleContent.vue'
import ArticleBubble from './components/ArticleBubble.vue'
</script>

<template>
  <h1 class="mb-5">Desktop-View</h1>
  <ArticleBubble>
    <ArticleContent title="A title" body="Some content here." />
  </ArticleBubble>
</template>

<style scoped></style>
