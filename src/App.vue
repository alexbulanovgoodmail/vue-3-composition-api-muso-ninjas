<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <div class="content">
    <RouterView />
  </div>
</template>

<style lang="scss">
.content {
  margin: 0 auto;
  max-width: 1200px;
  width: 100%;
  padding: 0 20px;
}
</style>
