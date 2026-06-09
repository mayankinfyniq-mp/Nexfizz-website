<template>
  <section class="w-full bg-[#F4EFEF] py-12 sm:py-16 lg:py-20">
    <div class="max-w-[1440px] mx-auto px-4 sm:px-6 md:px-8 lg:px-20 lg:h-[815px]">
      <!-- Header -->
      <div class="flex items-center justify-between mb-10 lg:mb-14">
        <h2
          class="text-[#17244B] font-extrabold text-[22px] sm:text-[26px] lg:text-[32px]"
          style="font-family: 'Nunito', sans-serif"
        >
          OUR PRODUCTS
        </h2>

        <!-- Arrows (Desktop Only) -->
        <div class="hidden lg:flex gap-4">
          <button
            class="w-16 h-16 rounded-full bg-white flex items-center justify-center text-[#17244B] text-4xl"
          >
            <img :src="left" alt="left arrow" class="w-[21.33px] h-[15.56] object-contain" />
          </button>

          <button
            class="w-16 h-16 rounded-full bg-white flex items-center justify-center text-[#17244B] text-4xl"
          >
            <img :src="right" alt="right arrow" class="w-[21.33px] h-[15.56] object-contain" />
          </button>
        </div>
      </div>

      <!-- Products Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-10">
        <!-- Card 1 -->
        <div class="bg-white rounded-[32px] p-6 sm:p-8 lg:p-10 flex flex-col">
          <img
            :src="appleBottle"
            alt="Apple Cider Vinegar"
            class="w-[150px] h-[200px] sm:w-[180px] sm:h-[240px] lg:w-[208px] lg:h-[278px] object-contain mx-auto"
          />

          <div class="mt-8 lg:mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-5 h-5 lg:w-6 lg:h-6" />
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> Apple • 15 Tablets </span>
          </div>

          <h3 class="mt-4 text-[20px] lg:text-[22px] font-bold">Apple Cider Vinegar</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div
            class="mt-6 lg:mt-8 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4"
          >
            <span class="text-[#F47C62] font-bold text-[20px] lg:text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-6 lg:px-8 py-3 lg:py-4 rounded-full text-[14px] lg:text-[15px] w-full sm:w-auto"
              style="font-family: 'Montserrat', sans-serif"
            >
              Add to Cart
            </button>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-[32px] p-6 sm:p-8 lg:p-10 flex flex-col">
          <img
            :src="electrolyteBottle"
            alt="Electrolyte"
            class="w-[150px] h-[200px] sm:w-[180px] sm:h-[240px] lg:w-[208px] lg:h-[278px] object-contain mx-auto"
          />

          <div class="mt-8 lg:mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-5 h-5 lg:w-6 lg:h-6" />
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> Lemon • 20 Tablets </span>
          </div>

          <h3 class="mt-4 text-[20px] lg:text-[22px] font-bold">Electrolyte</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div
            class="mt-6 lg:mt-8 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4"
          >
            <span class="text-[#F47C62] font-bold text-[20px] lg:text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-6 lg:px-8 py-3 lg:py-4 rounded-full text-[14px] lg:text-[15px] w-full sm:w-auto"
              style="font-family: 'Montserrat', sans-serif"
            >
              Add to Cart
            </button>
          </div>
        </div>

        <!-- Card 3 -->
        <div
          class="bg-white rounded-[32px] p-6 sm:p-8 lg:p-10 flex flex-col md:col-span-2 lg:col-span-1"
        >
          <img
            :src="glutathioneBottle"
            alt="Glutathione"
            class="w-[150px] h-[200px] sm:w-[180px] sm:h-[240px] lg:w-[208px] lg:h-[278px] object-contain mx-auto"
          />

          <div class="mt-8 lg:mt-10 flex items-center gap-2">
            <img :src="strawberryIcon" alt="" class="w-5 h-5 lg:w-6 lg:h-6" />
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> Strawberry • 15 Tablets </span>
          </div>

          <h3 class="mt-4 text-[20px] lg:text-[22px] font-bold">Glutathione</h3>

          <div class="mt-3 flex items-center gap-2">
            <span class="text-yellow-500 text-xl">★</span>
            <span class="text-[14px] lg:text-[16px] text-[#4D4D4D]"> 4.9 (245) </span>
          </div>

          <div
            class="mt-6 lg:mt-8 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4"
          >
            <span class="text-[#F47C62] font-bold text-[20px] lg:text-[22px]"> For ₹599 </span>

            <button
              class="bg-[#F47C62] text-white font-extrabold px-6 lg:px-8 py-3 lg:py-4 rounded-full text-[14px] lg:text-[15px] w-full sm:w-auto"
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
import left from '@/assets/icons/leftarrow.png'
import right from '@/assets/icons/rightarrow.png'
import strawberryIcon from '@/assets/icons/fruit.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
