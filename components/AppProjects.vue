<script setup>
const { data: websites, pending } = await useLazyFetch("/data/websites.json", {
  server: false,
});
</script>

<template>
  <div class="container">
    <h2 class="orange-text">Projects</h2>

    <h5>
      Below are projects I have worked on by myself, or with other team members
      throughout my career.
    </h5>

    <div v-if="pending">Loading ...</div>

    <div v-else class="projects">
      <div v-for="website in websites" class="project">
        <NuxtLink
          :to="website.url"
          external
          class="text-link project-title"
          target="_blank"
          >{{ website.name }}</NuxtLink
        >

        <div class="project-details">
          <p>{{ website.description }}</p>
        </div>

        <NuxtLink
          :to="website.url"
          external
          class="button button-dark"
          target="_blank"
        >
          Website
        </NuxtLink>

        <NuxtLink
          v-if="website.repo"
          :to="website.repo"
          external
          class="button button-dark"
          target="_blank"
        >
          Code
        </NuxtLink>
      </div>
    </div>
  </div>
</template>
