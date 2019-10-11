<template>
  <div class="container">
    <movies-list />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import MoviesList from "~/components/movies-list.vue";

export default {
  layout: 'layouts/default',
  components: {
    Logo,
    MoviesList
  }
};
</script>

<style>
  .card {
    min-width: 30%;
    max-width: 30%;
  }
</style>
