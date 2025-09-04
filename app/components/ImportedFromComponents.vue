<script setup lang="ts">
// No error when importing component explicitly.
import { MyEmitter } from "#components";
const hello = ref(false);
</script>
<template>
  <div>
    <MyEmitter @cool="(e) => (hello = e)" />
    {{ hello }}
  </div>
</template>
