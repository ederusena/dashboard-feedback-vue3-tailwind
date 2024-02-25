<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="flex gap-4 m-4 p-4 rounded bg-purple-200 justify-center">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/feedbacks">Feedbacks</RouterLink>
    <RouterLink to="/credentials">Credentials</RouterLink>
  </nav>

  <RouterView />
</template>