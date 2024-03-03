<script setup lang="ts">
const color = useColorMode()

useHead({
  meta: [{
    id: 'theme-color',
    name: 'theme-color',
    content: () => color.value === 'dark' ? '#1f2937' : '#ffffff',
  }],
})

function toggleDark() {
  color.preference = color.value === 'dark' ? 'light' : 'dark'
}
</script>

<template>
  <button class="social-icon !outline-none" @click="toggleDark">
    <div class="dark:i-carbon-asleep-filled i-carbon-light-filled" />
  </button>
</template>
