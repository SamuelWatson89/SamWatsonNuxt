<script>
import VueFeather from "vue-feather";

export default {
  components: {
    "vue-feather": VueFeather,
  },
};
</script>

<template>
  <footer class="container center-page">
    <div class="social">
      <div class="social-icon">
        <a href="https://github.com/SamuelWatson89">
          <vue-feather type="github" size="36" class="icon" />
        </a>
      </div>

      <div class="social-icon">
        <a href="https://linkedin.com/in/samuelwatson89">
          <vue-feather type="linkedin" size="36" class="icon" />
        </a>
      </div>

      <div class="social-icon">
        <a href="https://instagram.com/samuelwatson89/">
          <vue-feather type="instagram" size="36" class="icon" />
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  padding: 40px 0;
}
</style>
