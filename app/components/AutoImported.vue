<script setup lang="ts">
const hello = ref(false);
</script>
<template>
  <div>
    <MyEmitter @cool="(e) => (hello = e)" />
    <!--    Parameter 'e' implicitly has an 'any' type -->
    {{ hello }}
  </div>
</template>
