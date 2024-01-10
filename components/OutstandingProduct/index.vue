<script>
import Background from 'assets/images/reno11-5120-1280.jpg';

export default {
  props: {
    name: {
      type: String,
      default: ''
    },
    nickName: {
      type: String,
      default: ''
    }
  },
  data() {
    return {
      backgroundImage: { backgroundImage: `url(${Background})` }
    };
  }
};
</script>

<template>
  <div class="w-full bg-cover bg-center" :style="backgroundImage">
    <Container>
      <div class="h-[640px] flex flex-col justify-between items-start py-16 font-bold">
        <div class="flex flex-col gap-2">
          <h2 class="text-5xl">{{ name }}</h2>
          <h4 class="text-2xl">{{ nickName }}</h4>
        </div>
        <Button>Tìm hiểu thêm</Button>
      </div>
    </Container>
  </div>
</template>
