<script></script>
<template>
  <div class="py-16 bg-pink-50 bg-[url('~/assets/images/bg-pc.jpg')] bg-center bg-cover">
    <Container>
      <div class="flex flex-col gap-8">
        <div class="flex flex-col justify-center items-center gap-2">
          <h2 class="text-[32px]">Cập nhật mới nhất từ Oppo</h2>
          <p>
            Đăng ký để nhận ngay những thông tin ưu đãi, sản phẩm mới hay sự kiện đặc biệt từ OPPO!
          </p>
        </div>
        <form
          class="w-[32%] pl-8 pr-2 flex items-center gap-4 mx-auto rounded-full border border-[#efede9] bg-white"
        >
          <input placeholder="Email của bạn" class="flex-grow py-4 outline-none bg-transparent" />
          <button
            class="flex items-center justify-center h-[44px] aspect-square rounded-full bg-[#ebebeb]"
          >
            <Icon name="lucide:send-horizontal" />
          </button>
        </form>
        <div class="flex justify-center text-xs">
          <p class="text-center">
            Tôi muốn đăng ký để nhận thông tin từ OPPO và đối tác.<br />Khi đăng ký, bạn đồng ý với
            <span class="underline cursor-pointer">Chính sách quyền riêng tư của OPPO</span>
          </p>
        </div>
      </div>
    </Container>
  </div>
</template>
