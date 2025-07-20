<template>
  <div
    class="flex h-96 flex-col rounded-xl bg-[var(--mobena-soft-blue)] p-6 text-left hover:translate-y-[-10px] transition-all"
  >
    <img class="mb-4 h-48 w-full rounded-lg object-cover" :alt="imgAlt" :src="imgSrc" />
    <h3 class="mb-2 text-xl font-bold text-white">{{ title }}</h3>
    <p class="flex-grow text-white/90">
      {{ description }}
    </p>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  title: string
  description: string
  imgSrc: string
  imgAlt: string
}>()
</script>
