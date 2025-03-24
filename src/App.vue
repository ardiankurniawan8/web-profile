<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import DefaultLayout from './layouts/default.vue'
</script>

<template>
  <default-layout>
    <router-view />
  </default-layout>
</template>
