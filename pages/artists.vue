<script setup>
definePageMeta({
  key: route => route.fullPath
})

</script>

<template>
  <div>
    <div>Artists Page</div>

    <NuxtLink to="/artists/1/info">Info</NuxtLink>

    <NuxtPage page-key="static" />
  </div>
</template>
