<template>
  <section class="w-full bg-[#F47C62] overflow-hidden">
    <div class="relative mx-auto max-w-[1440px] min-h-screen lg:h-[776px]">
      <!-- Background Image (Desktop Only) -->
      <img
        :src="ctaBg"
        alt="Ready To Glow"
        class="hidden lg:block absolute inset-0 w-[1440px] h-[776px] object-cover"
      />

      <!-- Content -->
      <div class="relative z-10 h-full pt-16 px-6 md:px-10 lg:pt-[160px] lg:pl-[96px]">
        <!-- Heading -->
        <div class="w-full max-w-[543px] lg:w-[543px] lg:h-[72px]">
          <h2
            class="text-white text-[28px] md:text-[34px] lg:text-[40px] leading-[120%] font-extrabold"
            style="font-family: 'Nunito', sans-serif; font-weight: 800"
          >
            Ready to Glow from Within?
          </h2>

          <p
            class="mt-4 lg:mt-[24px] text-white text-[18px] md:text-[20px] lg:text-[24px] leading-[150%]"
            style="font-family: 'Montserrat', sans-serif; font-weight: 500"
          >
            Add NexFiz Glutathione to your daily routine and experience the next level of you.
          </p>
        </div>

        <!-- Benefits -->
        <div
          class="mt-16 md:mt-20 lg:mt-[140px] grid grid-cols-1 sm:grid-cols-2 gap-10 lg:gap-x-[64px] lg:gap-y-[64px] w-full max-w-[536px] lg:w-[536px] lg:h-[286px]"
        >
          <!-- Item 1 -->
          <div>
            <div
              class="w-[60px] h-[60px] rounded-full bg-white/15 flex items-center justify-center"
            >
              <img :src="icon1" alt="" class="w-[27.27px] h-[27.27px] object-contain" />
            </div>

            <h3
              class="mt-4 lg:mt-[24px] text-white text-[22px] lg:text-[26px] font-extrabold"
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
              class="mt-4 lg:mt-[24px] text-white text-[22px] lg:text-[26px] font-extrabold"
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
              class="mt-4 lg:mt-[24px] text-white text-[22px] lg:text-[26px] font-extrabold"
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
              class="mt-4 lg:mt-[24px] text-white text-[22px] lg:text-[26px] font-extrabold"
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
</style>
