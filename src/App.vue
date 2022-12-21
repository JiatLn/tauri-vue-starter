<script setup lang="ts">
const { x, y } = useMouse()
</script>

<template>
  <div flex="c col" h-100vh bg-white>
    <h1 color-brand-primary my-20px text="28px" flex-c >
      Welcome to Tauri! <div ml-4 inline-block i-logos:tauri />
    </h1>
    <div border p-4 my-3>
      Mouse ({{ x }}, {{ y }}) is over the window.
    </div>
    <Greet />
  </div>
</template>

<style scoped>

</style>
