<script setup lang="ts">
import type { NuxtError } from '#app'

const _props = defineProps<{
  error: NuxtError
}>()
</script>

<template>
  <div>
    <h1>Oh no</h1>
    <h1>{{ error.statusCode }}</h1>
    <NuxtLink to="/">
      Go back home
    </NuxtLink>
  </div>
</template>
