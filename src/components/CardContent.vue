<script setup>
const props = defineProps({
  title: String,
  description: String,
  image: String,
  links: Array
})
</script>
<template>
  <div class="grid grid-flow-col gap-4 p-4 cursor-pointer hover:rounded hover:bg-blue-950">
    <img :src="props.image" alt="HTML" class="h-36" />
    <div class="grid">
      <p class="font-bold text-gray-100 mb-2">
        {{ props.title }}
        <span class="material-symbols-outlined" style="font-size: 12px">north_east</span>
      </p>

      <p class="text-gray-400 mb-2">
        {{ props.description }}
      </p>
      <div class="grid-flow-col mt-4">
        <a
          v-for="(link, index) in props.links"
          :key="index"
          class="mb-2 mr-2 text-center inline-block rounded-full border-2 border-blue px-2 py-1 text-xs font-medium leading-normal text-blue-100 transition duration-150 ease-in-out hover:bg-blue-100 hover:text-blue-950 active:border-blue-900 active:text-blue-900 motion-reduce:transition-none"
        >
          {{ link }}
        </a>
      </div>
    </div>
  </div>
</template>
<style scoped></style>
