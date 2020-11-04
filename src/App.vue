<!-- the new ref sugar RFC, try it now! -->

<template>
  <button @click="inc">{{ count }} * 2 = {{ doubled }}</button>
</template>

<script setup>
import { computed } from 'vue'

ref: count = 0
ref: doubled = computed(() => count * 2)

const inc = () => count++
</script>
