<script setup lang="ts">
const { myLayer } = useAppConfig()

console.log(myLayer)
</script>

<template>
  <div>
    <h1>Hello World!</h1>
    <pre>{{ myLayer }}</pre>
  </div>
</template>
