<script setup>
import { computed } from 'vue'

ref: count = 0
ref: doubled = computed(() => count * 2)

const inc = () => count++
const dec = () => count -= 1
</script>

<template>
  <div>{{ count }} * 2 = {{ doubled }}</div>
  <button @click="dec">Dec</button>
  <button @click="inc">Inc</button>
</template>
