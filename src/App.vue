<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <nav class="fixed flex flex-col h-full p-4 space-y-4 font-semibold text-white bg-slate-600">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/detail">Detail</RouterLink>
    <RouterLink to="/guideline">Guideline</RouterLink>
  </nav>

  <RouterView />
</template>

<style src="./assets/index.scss">

</style>
<style lang="scss">

</style>
