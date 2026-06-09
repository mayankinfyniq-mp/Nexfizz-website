<template>
  <section class="w-full bg-[#F47C62] overflow-hidden">
    <div class="relative mx-auto max-w-[1440px] h-[776px]">
      <!-- Background Image -->
      <img
        :src="ctaBg"
        alt="Ready To Glow"
        class="absolute inset-0 w-[1440px] h-[776px] object-cover"
      />

      <!-- Content -->
      <div class="relative z-10 h-full pt-[160px] pl-[96px]">
        <!-- Heading -->
        <div class="w-[543px] h-[72px]">
          <h2
            class="text-white text-[40px] leading-[120%] font-extrabold"
            style="font-family: 'Nunito', sans-serif; font-weight: 800"
          >
            Ready to Glow from Within?
          </h2>

          <p
            class="mt-[24px] text-white text-[24px] leading-[150%]"
            style="font-family: 'Montserrat', sans-serif; font-weight: 500"
          >
            Add NexFiz Glutathione to your daily routine and experience the next level of you.
          </p>
        </div>

        <!-- Benefits -->
        <div class="mt-[140px] grid grid-cols-2 gap-x-[64px] gap-y-[64px] w-[536px] h-[286px]">
          <!-- Item 1 -->
          <div>
            <div
              class="w-[60px] h-[60px] rounded-full bg-white/15 flex items-center justify-center"
            >
              <img :src="icon1" alt="" class="w-[27.27px] h-[27.27px] object-contain" />
            </div>

            <h3
              class="mt-[24px] text-white text-[26px] font-extrabold"
              style="font-family: 'Nunito', sans-serif; font-weight: 800"
            >
              Glow Naturally
            </h3>
          </div>

          <!-- Item 2 -->
          <div>
            <div
              class="w-[60px] h-[60px] rounded-full bg-white/15 flex items-center justify-center"
            >
              <img :src="icon2" alt="" class="w-[27.27px] h-[27.27px] object-contain" />
            </div>

            <h3
              class="mt-[24px] text-white text-[26px] font-extrabold"
              style="font-family: 'Nunito', sans-serif; font-weight: 800"
            >
              Feel Energized
            </h3>
          </div>

          <!-- Item 3 -->
          <div>
            <div
              class="w-[60px] h-[60px] rounded-full bg-white/15 flex items-center justify-center"
            >
              <img :src="icon3" alt="" class="w-[27.27px] h-[27.27px] object-contain" />
            </div>

            <h3
              class="mt-[24px] text-white text-[26px] font-extrabold"
              style="font-family: 'Nunito', sans-serif; font-weight: 800"
            >
              Strong Immunity
            </h3>
          </div>

          <!-- Item 4 -->
          <div>
            <div
              class="w-[60px] h-[60px] rounded-full bg-white/15 flex items-center justify-center"
            >
              <img :src="icon4" alt="" class="w-[27.27px] h-[27.27px] object-contain" />
            </div>

            <h3
              class="mt-[24px] text-white text-[26px] font-extrabold"
              style="font-family: 'Nunito', sans-serif"
            >
              Better You
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import icon1 from '@/assets/logo/glow.png'
import icon2 from '@/assets/logo/energy.png'
import icon3 from '@/assets/logo/immunity.png'
import icon4 from '@/assets/logo/check.png'

import ctaBg from '@/assets/background/readybg.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
