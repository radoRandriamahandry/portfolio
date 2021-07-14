<template>
  <!-- TODO : use Slot name or props -->
  <section
    class="flex bg-white mt-14"
    :class="[reverseDirection && 'flex-row-reverse']"
  >
    <div class="flex-1">
      <div class="p-11">
        <p class="text-6xl font-bold text-gray-300">01.</p>
        <h3 class="mt-4 font-bold text-gray-600 text-2xl">
          Lorem ipsum dolor sit.
        </h3>
        <ul class="flex gap-3 text-sm mt-2">
          <li
            class="
              border border-green-400
              font-semibold
              text-green-400
              rounded-full
              px-2
            "
          >
            Vue3
          </li>
          <li class="border border-blue-400 text-blue-400 rounded-full px-2">
            TailwindCSS
          </li>
          <li
            class="border border-purple-400 text-purple-400 rounded-full px-2"
          >
            Vite
          </li>
        </ul>
        <p class="mt-3 leading-7 text-gray-500">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi sunt
          facilis quis dolorem maiores mollitia. Rerum, similique ea! Ut eveniet
          dolor praesentium voluptatem magnam incidunt quo dolorum, eum aperiam
          repellat.
        </p>
        <button
          class="
            mt-5
            px-3
            py-1
            rounded-full
            font-bold
            tracking-widest
            uppercase
            text-gray-400
            border-[3px] border-gray-400
          "
        >
          view project
        </button>
      </div>
    </div>
    <div
      class="
        bg-blue-300
        grid
        place-content-center
        font-bold
        text-white text-xl
        flex-1
      "
    >
      IMAGE
    </div>
  </section>
</template>

<script>
// TODO : props title, description, list of stack, link, image
export default {
  props: {
    reverseDirection: {
      type: Boolean,
      default: false,
    },
  },
}
</script>

<style></style>
