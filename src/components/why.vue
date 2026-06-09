<template>
  <section class="w-full bg-[#F4EFEF] overflow-hidden">
    <div class="mx-auto w-full max-w-[1440px] lg:h-[832px] flex flex-col lg:flex-row">
      <div class="w-full lg:w-[720px] lg:h-[832px] bg-[#F47C62] flex flex-col justify-center">
        <div class="px-8 sm:px-12 lg:px-[104px] py-16 lg:py-0">
          <div class="w-full max-w-[498px]">
            <h2
              class="text-white font-extrabold text-[34px] lg:text-[40px] leading-[150%]"
              style="font-family: 'Nunito', sans-serif"
            >
              Why Choose NexFiz?
            </h2>
            <p
              class="mt-5 text-white font-semibold text-[20px] lg:text-[24px] leading-[140%]"
              style="font-family: 'Manrope', sans-serif"
            >
              Experience the science-backed benefits of effervescent supplements
            </p>
          </div>
          <div class="mt-16 w-full max-w-[512px] space-y-10">
            <div class="flex items-center gap-6">
              <div
                class="w-[72px] h-[72px] rounded-full bg-white/20 flex items-center justify-center shrink-0"
              >
                <img :src="vegetarianIcon" alt="" class="w-9 h-9 object-contain" />
              </div>

              <div>
                <h3 class="text-white font-bold text-[22px]">100% Vegetarian</h3>

                <p class="mt-1 text-white/90 text-[16px] leading-[140%]">
                  Plant-based, cruelty-free formulas for everyone
                </p>
              </div>
            </div>
            <div class="flex items-center gap-6">
              <div
                class="w-[72px] h-[72px] rounded-full bg-white/20 flex items-center justify-center shrink-0"
              >
                <img :src="sugarFreeIcon" alt="" class="w-9 h-9 object-contain" />
              </div>

              <div>
                <h3 class="text-white font-bold text-[22px]">100% Sugar Free</h3>

                <p class="mt-1 text-white/90 text-[16px] leading-[140%]">
                  Delicious natural flavors without any added sugar
                </p>
              </div>
            </div>
            <div class="flex items-center gap-6">
              <div
                class="w-[72px] h-[72px] rounded-full bg-white/20 flex items-center justify-center shrink-0"
              >
                <img :src="fssaiIcon" alt="" class="w-9 h-9 object-contain" />
              </div>

              <div>
                <h3 class="text-white font-bold text-[22px]">FSSAI Approved</h3>

                <p class="mt-1 text-white/90 text-[16px] leading-[140%]">
                  Manufactured under strict quality standards
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="w-[4px] lg:h-[832px] bg-white shrink-0"></div>
      <div class="relative overflow-hidden w-full lg:w-[720px] lg:h-[832px] shrink-0">
        <img
          :src="whyChooseImage"
          alt="NexFiz Products"
          class="absolute inset-0 block w-[102%] h-[102%] -left-[1%] -top-[1%] object-cover object-center"
        />
      </div>
    </div>
  </section>
</template>

<script setup>
import whyChooseImage from '@/assets/background/bgof3.png'

import vegetarianIcon from '@/assets/img/vector.png'
import sugarFreeIcon from '@/assets/img/2nditem.png'
import fssaiIcon from '@/assets/img/3rditem.png'
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
