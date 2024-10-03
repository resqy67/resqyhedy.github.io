<script setup>
import LeftContent from './components/LeftContent.vue'
import RightContent from './components/RightContent.vue'
</script>

<template>
  <div class="min-h-screen bg-gradient-to-r from-blue-950 to-slate-950 text-white">
    <main class="container mx-auto p-4">
      <div class="grid grid-cols-1 gap-4 md:grid-cols-2">
        <LeftContent />
        <RightContent />
      </div>
    </main>
  </div>
</template>

<style scoped></style>
