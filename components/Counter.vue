<script setup>
import { ref } from 'vue'

const num = ref(0)

const onClick = () => {
  num.value++
}
</script>


<template>
  <p>{{ num }}</p>
  <button @click="onClick">click me</button>
</template>