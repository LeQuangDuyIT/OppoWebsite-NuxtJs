<script>
import { defineProps } from 'vue';

export default {
  props: {
    children: {
      type: [String, Array],
      default: ''
    }
  }
};
</script>

<template>
  <div>
    <div class="max-w-[1360px] w-full h-full mx-auto px-4 xl:px-0">
      <slot></slot>
    </div>
  </div>
</template>
