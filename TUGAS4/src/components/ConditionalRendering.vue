<script setup>
import { ref } from 'vue'

const awesome = ref(true)

function toggle() {
  awesome.value = !awesome.value
}
</script>

<template>
    <button @click="toggle">Toggle</button>
  <h1 v-if="awesome">SANGAT MENYENANGKAN!</h1>
  <h1 v-else>Oh TIDAKKK😢</h1>
</template>

<!-- SRI ADINDA_233510515 -->