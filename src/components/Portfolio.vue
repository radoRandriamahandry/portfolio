<template>
  <section class="max-w-screen-lg mx-auto mt-10">
    <h2 class="text-2xl font-bold">Projects</h2>
    <!-- TODO: portfolio wiht image, description, stack used and link to the project -->
    <PortfolioItem :reverse-direction="false" />
    <PortfolioItem :reverse-direction="true" />
    <PortfolioItem :reverse-direction="false" />
    <PortfolioItem :reverse-direction="true" />
  </section>
</template>

<script>
import PortfolioItem from "./PortfolioItem.vue"
export default {
  components: {
    PortfolioItem,
  },
}
</script>

<style></style>
