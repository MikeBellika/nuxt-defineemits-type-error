<script setup lang="ts">
// No error when importing component explitely.
import { MyEmitter } from "#components";
const hello = ref(false);
</script>
<template>
  <div>
    <MyEmitter @cool="(e) => (hello = e)" />
    {{ hello }}
  </div>
</template>
