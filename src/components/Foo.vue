<template>
  {{ foo }}
</template>

<script setup lang="ts">
defineProps<{
  foo: string;
}>();
</script>
