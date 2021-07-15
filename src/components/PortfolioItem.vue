<template>
  <!-- TODO : use Slot name or props -->
  <section
    class="flex bg-white mt-14"
    :class="[reverseDirection && 'flex-row-reverse']"
  >
    <div class="flex-1">
      <div class="p-11">
        <p class="text-6xl font-bold text-gray-300">01.</p>
        <h3 class="mt-4 text-2xl font-bold text-gray-600">
          Lorem ipsum dolor sit.
        </h3>
        <ul class="flex gap-3 mt-2 text-sm">
          <li
            class="px-2 tracking-widest text-green-500 bg-green-100 rounded-full "
          >
            Vue3
          </li>
          <li
            class="px-2 tracking-widest text-blue-500 bg-blue-100 rounded-full"
          >
            TailwindCSS
          </li>
          <li
            class="px-2 tracking-widest text-purple-500 bg-purple-100 rounded-full "
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
            align-text-top
          "
        >
          view project
        </button>
      </div>
    </div>
    <div
      class="grid flex-1 text-xl font-bold text-white bg-blue-300  place-content-center"
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
