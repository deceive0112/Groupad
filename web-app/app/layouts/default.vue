<script setup lang="ts">
</script><!-- layouts/default.vue -->
<template>
  <div class="bg-gray-900 text-gray-900 dark:text-white">
    <web-header/>
    <main>
      <!-- The page content will be injected here -->
      <slot/>
    </main>
    <web-footer/>
  </div>
</template>
