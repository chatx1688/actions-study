<script setup>
import HelloWorld from './components/HelloWorld.vue'

const buildTime = import.meta.env.VITE_BUILD_TIME
const buildAuthor = import.meta.env.VITE_BUILD_AUTHOR
</script>

<template>
  <HelloWorld />
  <footer>
    <p>最后构建于：{{ buildTime }}</p>
    <p>构建人：{{ buildAuthor }}</p>
  </footer>
</template>
