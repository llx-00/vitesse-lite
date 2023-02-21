<script setup lang="ts">
import { toggleDark } from '~/tools'
</script>

<template>
  <button icon-btn @click="toggleDark()">
    <div dark:i-carbon-moon i-carbon-sun />
  </button>
</template>
