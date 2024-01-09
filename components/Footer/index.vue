<script></script>
<template>
  <footer class="bg-black">
    <Container>
      <div class="flex justify-between gap-4 py-16 text-white">
        <div v-for="group in RENDER_FOOTER_NAVIGATE">
          <div>
            <h5 class="mb-4 font-bold">{{ group.title }}</h5>
            <div class="flex flex-col gap-1.5">
              <div v-for="item in group.children">
                <a class="text-white/55 hover:text-white cursor-pointer">{{ item.title }}</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="py-6 border-t border-t-white/15">
        <p class="text-white/55 text-center">
          Copyright © 2004-2024 Le Quang Duy. All rights reserved.
        </p>
      </div>
    </Container>
  </footer>
</template>
