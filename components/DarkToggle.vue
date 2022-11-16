<script setup lang="ts">
const color = useColorMode()

function toggleDark() {
  color.value = color.value === 'dark' ? 'light' : 'dark'
}
</script>

<template>
  <button class="!outline-none" @click="toggleDark">
    <div class="w8 h8 dark:(w8 h8) dark:i-carbon-moon i-carbon-sun " />
  </button>
</template>
