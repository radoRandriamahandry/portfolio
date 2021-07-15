<template>
  <div class="bg-blue-100 h-72">
    <div class="grid items-center h-full max-w-screen-lg mx-auto">
      <div>
        <h1 class="text-4xl font-bold text-blue-900">
          I'm a Frontend Developper.
        </h1>
        <h2 class="mt-2">
          My name is <span class="font-semibold">Rado Randriamahandry.</span>
        </h2>
        <!-- TODO: create animation for showing Vue3, tailwindcss, graphql one after the other -->
        <!-- use type machine style -->
        <p class="w-1/3 mt-2 text-sm leading-tight text-gray-500">
          We'll make your App or Website beautiful, modern and stylish.
        </p>
        <button
          class="px-3 py-2 mt-5 text-xs font-bold tracking-wider uppercase align-text-top bg-blue-900 rounded-full  text-blue-50"
        >
          Contact me
        </button>
      </div>
    </div>
  </div>
  <Portfolio />
</template>

<script>
import Portfolio from "./Portfolio.vue"
export default {
  components: {
    Portfolio,
  },
}
</script>

<style></style>
