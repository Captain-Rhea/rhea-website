<script setup lang="ts">
const emit = defineEmits(['click']);
</script>

<template>
  <button @click="$emit('click')" class="px-4 py-2 border rounded-md text-lg">
    <slot>CTA Button</slot>
  </button>
</template>
