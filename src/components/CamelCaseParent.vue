<script setup lang="ts">
import CamelCaseChild from '@/components/CamelCaseChild.vue'
import { ref } from 'vue'

// type Props = {
//   camelCase: string
// }
// defineProps<Props>()

const camelCase = ref('Hey!')
</script>

<template>
  <CamelCaseChild :camel-case />
</template>

<style scoped></style>
