<script>
import { defineProps } from 'vue';

export default {
  props: {
    children: {
      type: [String, Array],
      default: 'Click me'
    }
  }
};
</script>
<template>
  <button class="bg-black text-white px-4 py-2 rounded-full">
    <slot></slot>
  </button>
</template>
