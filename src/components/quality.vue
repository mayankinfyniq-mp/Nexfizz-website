<template>
  <section class="hidden lg:block w-full bg-[#F4EFEF] overflow-hidden">
    <div class="relative mx-auto w-full max-w-[1440px] h-[927px]">
      <img :src="benefitsBg" alt="Benefits" class="block w-auto h-full" />

      <div class="absolute inset-0 flex flex-col items-center justify-center">
        <div class="space-y-16">
          <div
            class="w-[342px] h-[206px] bg-white rounded-[32px] flex flex-col items-center justify-center"
          >
            <img :src="sweetenerIcon" alt="" class="w-14 h-14 mb-4" />

            <h3 class="text-[#F47C62] text-center font-bold text-[25px] leading-[130%]">
              NO ARTIFICIAL
              <br />
              SWEETNERS
            </h3>
          </div>

          <div
            class="w-[342px] h-[206px] bg-white rounded-[32px] flex flex-col items-center justify-center"
          >
            <img :src="hydrationIcon" alt="" class="w-14 h-14 mb-4" />

            <h3 class="text-[#F47C62] text-center font-bold text-[25px] leading-[130%]">
              FASTER HYDRATION
              <br />
              SUPPORT
            </h3>
          </div>

          <div
            class="w-[342px] h-[206px] bg-white rounded-[32px] flex flex-col items-center justify-center"
          >
            <img :src="absorptionIcon" alt="" class="w-14 h-14 mb-4" />

            <h3 class="text-[#F47C62] text-center font-bold text-[25px] leading-[130%]">
              3X FASTER
              <br />
              ABSORPTION
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import benefitsBg from '@/assets/background/benefitbg.png'

import sweetenerIcon from '@/assets/icons/sweetener.png'
import hydrationIcon from '@/assets/icons/hydration.png'
import absorptionIcon from '@/assets/icons/absorption.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
