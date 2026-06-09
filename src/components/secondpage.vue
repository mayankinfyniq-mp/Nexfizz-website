<template>
  <section class="w-full bg-[#F4EFEF] overflow-hidden">
    <div class="relative mx-auto w-full max-w-[1440px] h-[656px]">
      <div class="hidden lg:block">
        <div
          class="absolute top-[160px] left-[96px] w-[80px] h-[80px] bg-white rounded-[24px] flex items-center justify-center shadow-sm"
        >
          <img :src="med" alt="Logo" class="w-[50.91px] h-[50.91px] object-contain" />
        </div>
        <div class="absolute top-[280px] left-[96px] right-[96px]">
          <h2
            class="font-extrabold text-[40px] leading-[150%] text-[#17244B]"
            style="font-family: 'Nunito', sans-serif; font-weight: 800"
          >
            Premium Effervescent Supplements Crafted for Faster
            <br />

            Absorption,

            <span
              class="inline-flex items-center justify-center px-[5px] py-[7px] rounded-[19px] bg-[#F47C62] text-white font-extrabold text-[40px] leading-[150%]"
            >
              Better Taste
            </span>

            and Everyday Wellness Support
          </h2>
        </div>
        <div class="absolute top-[500px] left-[96px] right-[172px]">
          <p
            class="font-semibold text-[20px] leading-[140%] text-[#5A607A]"
            style="font-family: 'Manrope', sans-serif"
          >
            NexFiz combines refreshing effervescent nutrition with scientifically crafted formulas
            designed to support hydration, energy, immunity, skin health, and overall daily wellness
            in a more enjoyable way.
          </p>
        </div>
      </div>
      <div class="lg:hidden px-6 py-16">
        <div
          class="w-[72px] h-[72px] bg-white rounded-[20px] flex items-center justify-center shadow-sm"
        >
          <img :src="med" alt="Logo" class="w-[28px] h-[28px] object-contain" />
        </div>
        <div class="mt-10">
          <h2
            class="text-[40px] sm:text-[34px] font-extrabold leading-[150%] text-[#17244B]"
            style="font-family: 'Nunito', sans-serif"
          >
            Premium Effervescent Supplements Crafted for Faster Absorption,

            <span class="inline-block px-2 rounded-[20px] bg-[#F47C62] text-white">
              Better Taste
            </span>

            and Everyday Wellness Support
          </h2>
        </div>
        <p
          class="mt-8 text-[16px] sm:text-[18px] font-semibold leading-[140%] text-[#5A607A]"
          style="font-family: 'Manrope', sans-serif"
        >
          NexFiz combines refreshing effervescent nutrition with scientifically crafted formulas
          designed to support hydration, energy, immunity, skin health, and overall daily wellness
          in a more enjoyable way.
        </p>
      </div>
    </div>
  </section>
</template>

<script setup>
import med from '@/assets/icons/medicine.png'
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
