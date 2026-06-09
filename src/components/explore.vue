<template>
  <section class="w-full bg-[#FEF2F4] overflow-hidden">
    <!-- Page Container -->
    <div class="mx-auto max-w-[1440px] h-[756px] px-[88px] py-[112px] box-border">
      <!-- White Card -->
      <div
        class="w-[1264px] h-[532px] bg-[#F7F7F7] rounded-[24px] p-[24px] box-border flex items-center"
      >
        <!-- Left Image -->
        <div class="w-[514px] h-[484px] shrink-0">
          <img :src="productImg" alt="Product" class="w-full h-full object-cover rounded-[24px]" />
        </div>

        <!-- Right Content -->
        <div class="ml-[64px] w-[560px]">
          <h2
            class="text-[#15213B] text-[51px] leading-[115%] font-extrabold"
            style="font-family: 'Nunito', sans-serif; font-weight: 800"
          >
            Refreshing<br />
            effervescent formulas<br />
            for daily wellness.
          </h2>

          <p
            class="mt-[32px] text-[#15213B] text-[19px] leading-[150%] font-semibold"
            style="font-family: 'Manrope', sans-serif; font-weight: 600"
          >
            Fast-absorbing fizzy wellness formulas for everyday health.
          </p>

          <button
            class="mt-[40px] w-[232px] h-[68px] rounded-full bg-[#F47C62] text-white text-[17px] font-extrabold hover:opacity-90 transition"
            style="font-family: 'Nunito', sans-serif; font-weight: 800"
          >
            Explore Products
          </button>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import productImg from '@/assets/background/explorebg.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
