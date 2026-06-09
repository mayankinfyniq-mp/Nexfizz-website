<template>
  <section class="relative bg-[#FDF2E5] overflow-hidden min-h-168">
    <div class="hidden xl:block absolute inset-y-0 right-[-2%] overflow-hidden" style="width: 100%">
      <div
        class="absolute left-0 top-0 h-full w-40 z-10 bg-linear-to-r from-[#FDF2E5] to-transparent"
      ></div>
      <img
        :src="bg1"
        alt="background"
        class="hero bg h-full max-w-150 sm:max-w-165 lg:max-w-none lg:w-full object-contain"
        style="
          mask-image: linear-gradient(
            to right,
            black 0%,
            black 70%,
            rgba(0, 0, 0, 0.8) 80%,
            rgba(0, 0, 0, 0.4) 90%,
            transparent 100%
          );

          -webkit-mask-image: linear-gradient(
            to right,
            black 0%,
            black 70%,
            rgba(0, 0, 0, 0.8) 80%,
            rgba(0, 0, 0, 0.4) 90%,
            transparent 100%
          );
        "
      />
      <div
        class="absolute top-0 right-0 h-full w-90"
        style="
          background: linear-gradient(
            to right,
            rgba(253, 242, 229, 0) 0%,
            rgba(253, 242, 229, 1) 100%
          );
        "
      ></div>
    </div>
    <!-- Mobile Background Image -->
    <img
      :src="bg2"
      alt="background"
      class="block xl:hidden absolute bottom-0 left-0 w-full object-cover object-bottom"
    />
    <div class="relative z-10 max-w-360 mx-auto px-6 lg:px-16 py-10 lg:py-12">
      <div class="flex flex-col lg:flex-row items-center justify-between gap-10">
        <!-- Left Text Content -->
        <div class="w-full lg:w-1/2 xl:w-2/5 text-center lg:text-left">
          <h1
            class="text-3xl sm:text-4xl md:text-5xl lg:text-5xl xl:text-6xl font-bold leading-tight text-[#26345F]"
          >
            The Next Level of
            <br />
            <span class="text-[#F47C62]">Nutrition Fizz</span>
          </h1>

          <p
            class="mt-4 lg:mt-6 text-gray-700 text-sm sm:text-base lg:text-lg max-w-md mx-auto lg:mx-0"
          >
            NexFiz Glutathione helps you glow from within. Backed by science. Loved by thousands.
          </p>

          <div class="mt-6 lg:mt-8 flex flex-wrap justify-center lg:justify-start gap-4">
            <button
              class="px-5 py-2.5 lg:px-6 lg:py-3 bg-[#F47B63] text-white rounded-full font-medium hover:bg-[#F47C62] text-sm lg:text-base"
            >
              Explore Products
            </button>

            <button
              class="px-5 py-2.5 lg:px-6 lg:py-3 border border-[#F47C62] text-[#F47C62] rounded-full font-medium hover:bg-[#F47C62] hover:text-white text-sm lg:text-base"
            >
              Contact Us
            </button>
          </div>

          <div class="mt-8 lg:mt-12 grid grid-cols-3 gap-4 lg:gap-10 text-center">
            <div>
              <h3 class="text-[#F47C62] text-xl lg:text-2xl font-bold">15+</h3>
              <p class="text-xs lg:text-sm text-gray-600">Products</p>
            </div>
            <div>
              <h3 class="text-[#F47C62] text-xl lg:text-2xl font-bold">100k+</h3>
              <p class="text-xs lg:text-sm text-gray-600">Happy Customers</p>
            </div>
            <div>
              <h3 class="text-[#F47C62] text-xl lg:text-2xl font-bold">100%</h3>
              <p class="text-xs lg:text-sm text-gray-600">Sugar Free</p>
            </div>
          </div>
        </div>

        <!-- Right spacer -->
        <div class="hidden lg:block w-full lg:w-1/2 xl:w-3/5" style="min-height: 500px"></div>
        <div class="block lg:hidden w-full" style="padding-bottom: 110%"></div>
      </div>
    </div>
  </section>
</template>

<script setup>
import bg1 from '@/assets/background/desktopbg.png'
import bg2 from '@/assets/background/mobilebg.png'
</script>
