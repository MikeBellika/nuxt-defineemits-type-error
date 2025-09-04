<script setup lang="ts">
defineEmits<{ cool: [value: boolean] }>();
</script>
<template>
  <button @click="$emit('cool', true)">emit</button>
</template>
