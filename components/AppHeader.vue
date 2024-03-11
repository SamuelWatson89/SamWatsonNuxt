<script setup>
useHead({
  title: "Sam Watson - Full stack developer",
  meta: [
    {
      name: "description",
      content: "Personal website for Sam Watson, a full stack web developer.",
    },
  ],
  bodyAttrs: {
    class: "body",
  },
});

useSeoMeta({
  title: "Sam Watson - Full stack developer",
  ogTitle: "Sam Watson - Full stack developer",
  description: "Personal website for Sam Watson, a full stack web developer.",
  ogDescription: "Personal website for Sam Watson, a full stack web developer.",
  ogImage: "https://example.com/image.png",
  twitterCard: "summary_large_image",
});
</script>

<template>
  <header class="container">
    <nav class="main-nav">
      <NuxtLink to="/" class="nav-link">Home 🏠</NuxtLink>

      <NuxtLink to="/about" class="nav-link">About 🙋</NuxtLink>

      <NuxtLink
        to="https://github.com/SamuelWatson89"
        class="nav-link"
        external
        target="_blank"
        >GitHub 📎</NuxtLink
      >
    </nav>
  </header>
</template>
