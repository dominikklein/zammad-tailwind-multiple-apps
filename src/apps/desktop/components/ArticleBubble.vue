<script setup lang="ts"></script>

<template>
  <div class="Article bg-blue-50">
    <div class="Internal">
      <div class="Border">
        <slot />
      </div>
    </div>
  </div>
</template>

<style scoped>
.Internal .Border {
  background: repeating-linear-gradient(
    45deg,
    theme('colors.blue.50'),
    theme('colors.blue.50') 5px,
    theme('colors.blue.900') 5px,
    theme('colors.blue.900') 10px
  );
}
</style>
