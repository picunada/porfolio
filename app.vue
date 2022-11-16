<script setup>
useHead({
  title: 'Picunada',
  link: [
    {
      rel: 'icon', type: 'image/png', href: '/icon.svg',
    },
  ],
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
html, body , #__nuxt{
  height: 100vh;
  margin: 0;
  padding: 0;
}

html.dark {
  background: #111;
  color: white;
}
</style>
