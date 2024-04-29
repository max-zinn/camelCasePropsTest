<script setup lang="ts">
type Props = {
  camelCase: string;
};
defineProps<Props>();
</script>

<template>
<h1>{{camelCase}}</h1>
</template>

<style scoped>

</style>
