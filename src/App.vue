<script setup lang="ts">
  const a = import.meta.glob('./views/**/*.vue')
  console.log(a, 'a==')
</script>

<template>
  <router-view />
</template>

