<script lang="ts" setup>
useHead({
  title: 'Home',
  meta: [
    {
      name: 'description',
      content:
       'Explore the World of Web Development on My Blog. Find insightful articles, tips, and learning resources covering a spectrum of technologies, including React, Vue, Next.js, Nuxt.js, Node.js, Express, PHP, Laravel, and more. Elevate your coding journey with valuable insights and practical knowledge.',
    },
  ],
  titleTemplate: 'Aziz Limonu',
})

// a. Use the Composition API
defineOgImage({
  title: 'Aziz\'s Blog',
  description: 'Explore the World of Web Development on My Blog. Find insightful articles, tips, and learning resources covering a spectrum of technologies, including React, Vue, Next.js, Nuxt.js, Node.js, Express, PHP, Laravel, and more. Elevate your coding journey with valuable insights and practical knowledge.',
})
</script>

<template>
  <main class="container max-w-5xl mx-auto text-zinc-600">
    <MainHero />
    <MainRecent />
    <MainTrending />
  </main>
</template>
