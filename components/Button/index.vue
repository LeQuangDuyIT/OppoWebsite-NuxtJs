<script>
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
  <button class="bg-black hover:bg-black/70 duration-300 text-white px-4 py-2 rounded-full">
    <slot></slot>
  </button>
</template>
