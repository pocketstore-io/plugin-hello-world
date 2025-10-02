<template>
  <section class="bg-white xl:mx-auto mx-3 px-3 py-3 max-w-6xl">
    Hallo Welt {{ version}}
  </section>
</template>

<script setup lang="ts">
const version = ref('0.0.1.3');
</script>