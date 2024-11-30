import {createRouter, createWebHistory} from "vue-router";

<script setup>


</script>

<template lang="pug">
  div
    router-link(to="/") Home
    |
    router-link(to="/about") About
    router-view

</template>

<style scoped>


@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
