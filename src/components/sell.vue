<template>
  <section class="w-full bg-[#F4EFEF] py-20">
    <div class="max-w-[1440px] h-[815px] mx-auto px-6 lg:px-20">
      <div class="flex items-center justify-between mb-14">
        <h2
          class="text-[#17244B] font-extrabold text-[26px] lg:text-[32px]"
          style="font-family: 'Nunito', sans-serif"
        >
          OUR PRODUCTS
        </h2>

        <div class="hidden lg:flex gap-4">
          <button
            class="w-16 h-16 rounded-full bg-white flex items-center justify-center text-[#17244B] text-4xl"
          >
            ←
          </button>

          <button
            class="w-16 h-16 rounded-full bg-white flex items-center justify-center text-[#17244B] text-4xl"
          >
            →
          </button>
        </div>
      </div>
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-10">
        <div class="bg-white rounded-[32px] p-10 flex flex-col">
          <img
            :src="appleBottle"
            alt="Apple Cider Vinegar"
            class="w-[208px] h-[278px] object-contain mx-auto"
          />

          <div class="mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-6 h-6" />
            <span class="text-[16px] text-[#4D4D4D]"> Apple • 15 Tablets </span>
          </div>

          <h3 class="mt-4 text-[22px] font-bold">Apple Cider Vinegar</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div class="mt-8 flex items-center justify-between">
            <span class="text-[#F47C62] font-bold text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-8 py-4 rounded-full text-[15px]"
              style="font-family: 'Montserrat', sans-serif"
            >
              Add to Cart
            </button>
          </div>
        </div>
        <div class="bg-white rounded-[32px] p-10 flex flex-col">
          <img
            :src="electrolyteBottle"
            alt="Electrolyte"
            class="w-[208px] h-[278px] object-contain mx-auto"
          />

          <div class="mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-6 h-6" />
            <span class="text-[16px] text-[#4D4D4D]"> Lemon • 20 Tablets </span>
          </div>

          <h3 class="mt-4 text-[22px] font-bold">Electrolyte</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div class="mt-8 flex items-center justify-between">
            <span class="text-[#F47C62] font-bold text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-8 py-4 rounded-full text-[15px]"
              style="font-family: 'Montserrat', sans-serif"
            >
              Add to Cart
            </button>
          </div>
        </div>
        <div class="bg-white rounded-[32px] p-10 flex flex-col">
          <img
            :src="glutathioneBottle"
            alt="Glutathione"
            class="w-[208px] h-[278px] object-contain mx-auto"
          />

          <div class="mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-6 h-6" />
            <span class="text-[16px] text-[#4D4D4D]"> Strawberry • 15 Tablets </span>
          </div>

          <h3 class="mt-4 text-[22px] font-bold">Glutathione</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div class="mt-8 flex items-center justify-between">
            <span class="text-[#F47C62] font-bold text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-8 py-4 rounded-full text-[15px] hover"
              style="font-family: 'Montserrat', sans-serif"
            >
              Add to Cart
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import appleBottle from '@/assets/logo/apple.png'
import electrolyteBottle from '@/assets/logo/lemon.png'
import glutathioneBottle from '@/assets/logo/strawberry.png'

import strawberryIcon from '@/assets/icons/fruit.png'
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
