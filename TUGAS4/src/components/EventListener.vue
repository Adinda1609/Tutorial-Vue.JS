<script setup>
import { ref } from 'vue'
const count = ref(5)
function increment() {
  count.value++
}
</script>

<template>
  <button @click="increment">Count is: {{ count }}</button>
</template>

<!-- SRI ADINDA_233510515 -->