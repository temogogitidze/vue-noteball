<template>
  <RouterLink class="button" to="/">Notes</RouterLink> |
  <RouterLink class="button" to="/stats">Stats</RouterLink>
  <RouterView />
</template>

<script setup>
import { RouterView } from 'vue-router'
import NavBar from '@/components/layouts/NavBar.vue'
</script>

<style>
@import 'bulma/css/bulma.min.css';
</style>
