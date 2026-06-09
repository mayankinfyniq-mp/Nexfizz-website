<template>
  <div class="hidden md:block bg-[#0B1D4A] text-white">
    <div
      class="max-w-360 h-[56px] mx-auto h-14 px-6 lg:px-22 lg:py-2 flex items-center justify-between"
    >
      <div class="flex items-center text-sm lg:text-base gap-8">
        <span class="gap-8">100% Vegetarian</span>

        <div class="h-8 w-px bg-white/30"></div>

        <span class="gap-8">Sugar Free</span>

        <div class="h-8 w-px bg-white/30"></div>

        <span class="gap-8">Premium Effervescent Supplements</span>
      </div>
      <div class="flex items-center gap-3">
        <img :src="call" alt="Phone" class="w-5 h-5 object-contain" />

        <span class="text-sm lg:text-base whitespace-nowrap"> (+91) 9408516466 / 9429761637 </span>
      </div>
    </div>
  </div>
</template>
<script setup>
import call from '@/assets/icons/callicon.png'
</script>
