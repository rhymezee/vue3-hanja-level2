<template>
  <div>
    Hello World!
  </div>
</template>

<script setup>
  import { useDark, useToggle } from '@vueuse/core'

  const isDark = useDark()
  const toggleDark = useToggle(isDark)
</script>

<style scoped>

</style>