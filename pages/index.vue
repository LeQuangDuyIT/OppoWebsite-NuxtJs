<script></script>
<template>
  <div>
    <div class="flex flex-col gap-0.5">
      <OutstandingProduct name="OPPO Reno11" nickName="Chuyên gia chân dung" />
      <OutstandingProduct name="OPPO Find N3" nickName="Bậc thầy gập mở" />
      <OutstandingProduct name="OPPO Find N3 Flip" nickName="Gập để tỏa sáng" />
    </div>
    <Container>
      <div class="flex gap-1 flex-wrap mt-1">
        <ProductCart class="w-[calc(50%-4px/2)]" />
        <ProductCart class="w-[calc(50%-4px/2)]" />
        <ProductCart class="w-[calc(50%-4px/2)]" />
        <ProductCart class="w-[calc(50%-4px/2)]" />
      </div>
    </Container>
    <div class="bg-[#E0E8EA]">
      <Container>
        <div class="flex gap-2 flex-wrap mt-1 py-16">
          <DiscoverCard class="w-[calc(33.33%-8px*2/3)]" />
          <DiscoverCard class="w-[calc(33.33%-8px*2/3)]" />
          <DiscoverCard class="w-[calc(33.33%-8px*2/3)]" />
        </div>
      </Container>
    </div>
    <div>
      <RegisterForm />
    </div>
  </div>
</template>
