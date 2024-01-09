<script>
export default {
  props: {
    title: {
      type: String,
      default: ''
    },
    description: {
      type: String,
      default: ''
    }
  }
};
</script>
<template>
  <div class="flex flex-col cursor-pointer">
    <div>
      <img src="~/assets/images/About-OPPO.jpg.thumb.webp" />
    </div>
    <div class="flex flex-col gap-8 p-6 bg-white">
      <h3 class="text-xl font-bold">Khám phá Oppo</h3>
      <div class="flex justify-between items-center">
        <p class="w-[80%]">
          Câu chuyện đằng sau một trong những công ty công nghệ hàng đầu thế giới
        </p>
        <Icon name="material-symbols:arrow-right-alt" class="text-4xl cursor-pointer" />
      </div>
    </div>
  </div>
</template>
