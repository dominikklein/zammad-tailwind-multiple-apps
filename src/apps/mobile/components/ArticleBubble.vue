<script setup lang="ts"></script>

<template>
  <div class="Article">
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
    theme('colors.blue.DEFAULT'),
    theme('colors.blue.DEFAULT') 5px,
    theme('colors.blue.dark') 5px,
    theme('colors.blue.dark') 10px
  );
}
</style>
