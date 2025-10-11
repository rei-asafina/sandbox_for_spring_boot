<script setup lang="ts">
import Home from "./views/Home.vue";
import Lifecycle from "./components/Lifecycle.vue";
</script>
<template>
  <div class="app">
    <main class="view">
      <RouterView />
    </main>
  </div>
</template>

<style>
/* 不要なら starter の CSS は削除してOK */
</style>
