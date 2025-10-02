<template>
  <section class="bg-white xl:mx-auto mx-3 px-3 py-3 max-w-6xl">
    Hallo Welt {{ config.version}}
  </section>
</template>

<script setup lang="ts">
import config from '../plugin.json'
</script>