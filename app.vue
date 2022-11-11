<script setup lang="ts">
const title = 'Nuxt 3 Starter'
useHead({
  htmlAtrs: { lang: 'en' },
  charset: 'utf-8',
  title,
  titleTemplate: t => t !== title ? `${t} · ${title}` : t,
  meta: [],
  link: [],
})
</script>

<template>
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
</template>

<style lang="sass">
html, body , #__nuxt
  height: 100vh
  margin: 0
  padding: 0
</style>
