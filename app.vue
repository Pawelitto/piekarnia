<script setup lang="ts">
useHead({
  meta: [{ name: 'viewport', content: 'width=device-width, initial-scale=1' }],
  link: [{ rel: 'icon', href: '/favicon.ico' }],
  htmlAttrs: {
    lang: 'pl',
  },
});

useSeoMeta({
  ogImage: 'https://i.ibb.co/tHd4w5C/banner.jpg',
  twitterImage: 'https://i.ibb.co/tHd4w5C/banner.jpg',
  twitterCard: 'summary_large_image',
  ogUrl: 'https://i.ibb.co/tHd4w5C/banner.jpg',
  twitterTitle: 'Piekarnia Tomasz Barański - Najlepsze Pieczywo i Ciasta',
  twitterDescription:
    'Oferujemy codziennie świeże pieczywo, pyszne ciasta i szeroki wybór wypieków. Odwiedź nasz sklep i skosztuj naszych wyrobów, tworzonych z pasją i najlepszych składników.',
});
</script>

<template>
  <Header />

  <UMain>
    <NuxtPage />
  </UMain>

  <Footer />
  <UNotifications />
</template>
