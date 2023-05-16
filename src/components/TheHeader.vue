<script setup>
import { PAGE_TIMELINE, PAGE_PROGRESS } from '../constants'
import { isPageValid } from '../validators'
import TheLogo from './TheLogo.vue'
import TheHeaderProgress from './TheHeaderProgress.vue'
const emit = defineEmits({
  navigate: isPageValid
})
</script>

<template>
  <header class="sticky top-0 z-20 flex items-center justify-between p-3 bg-white border-b">
    <TheLogo @click="emit('navigate', PAGE_TIMELINE)" />
    <TheHeaderProgress @click="emit('navigate', PAGE_PROGRESS)" />
  </header>
</template>