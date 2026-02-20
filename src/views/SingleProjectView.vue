<template>
  <div>
    <h1>Single Project View for {{ route.params?.id }}</h1>
  </div>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router'
const route = useRoute()
console.log('Route params:', route.params)
</script>

<style scoped></style>
