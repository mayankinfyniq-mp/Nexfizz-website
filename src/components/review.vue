```vue
<template>
  <section class="w-full bg-[#FEF2F4] overflow-hidden">
    <div
      class="mx-auto max-w-[1440px] px-4 sm:px-6 md:px-10 lg:px-[88px] py-12 lg:pt-[152px] lg:pb-[112px]"
    >
      <!-- White Container -->
      <div
        class="relative w-full lg:w-[1264px] min-h-fit lg:h-[564px] bg-[#F7F7F7] rounded-[24px] p-6 md:p-8 lg:p-[56px] box-border"
      >
        <!-- Satisfaction Badge -->
        <div
          class="absolute right-4 top-4 md:right-8 md:top-6 lg:top-[-52px] lg:right-[128px] w-[110px] h-[110px] md:w-[140px] md:h-[140px] lg:w-[187.08px] lg:h-[187.72px] rotate-[13.3deg]"
        >
          <img :src="badgeBorder" alt="" class="absolute inset-0 w-full h-full object-contain" />

          <img
            :src="badgeFill"
            alt=""
            class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 w-[80px] h-[80px] md:w-[105px] md:h-[105px] lg:w-[142.37px] lg:h-[143.73px] object-contain"
          />

          <div class="absolute inset-0 flex flex-col items-center justify-center text-white">
            <div
              class="text-[24px] md:text-[36px] lg:text-[48px] font-extrabold leading-none"
              style="font-family: 'Nunito', sans-serif"
            >
              100%
            </div>

            <div
              class="text-[10px] md:text-[16px] lg:text-[21.5px] uppercase font-extrabold"
              style="font-family: 'Nunito', sans-serif"
            >
              Satisfied
            </div>
          </div>
        </div>

        <!-- Header -->
        <div class="pr-24 lg:pr-0">
          <h2
            class="text-[#15213B] text-[24px] md:text-[28px] lg:text-[32px] leading-[120%] font-extrabold"
            style="font-family: 'Nunito', sans-serif"
          >
            What Our Customers Say
          </h2>

          <p
            class="mt-4 text-[14px] md:text-[16px] lg:text-[17px] leading-[150%] text-[#505050] max-w-[700px]"
            style="font-family: 'Manrope', sans-serif"
          >
            Join thousands of happy customers who've made NexFiz part of their daily wellness
            routine
          </p>
        </div>

        <!-- Cards -->
        <div
          class="mt-8 lg:mt-[40px] grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-[40px]"
        >
          <!-- Card 1 -->
          <div
            class="w-full lg:w-[362.67px] min-h-[280px] lg:h-[330px] bg-[#F1F1F1] rounded-[24px] p-6 lg:p-[32px]"
          >
            <img :src="quoteImg" alt="Quote" class="w-[30px] h-auto lg:w-[37px]" />

            <p
              class="mt-3 text-[15px] md:text-[16px] lg:text-[18px] font-semibold leading-[150%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif"
            >
              I've been using NexFiz Glutathione for a month now and my skin looks brighter and more
              radiant. Absolutely love the strawberry flavor!
            </p>

            <div class="mt-6 lg:mt-[32px] border-t border-[#D8D8D8] pt-4">
              <h4
                class="text-[16px] lg:text-[18px] font-bold text-[#15213B]"
                style="font-family: 'Nunito', sans-serif"
              >
                Priya Sharma
              </h4>

              <p
                class="mt-2 text-[15px] lg:text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif"
              >
                Mumbai
              </p>
            </div>
          </div>

          <!-- Card 2 -->
          <div
            class="w-full lg:w-[362.67px] min-h-[280px] lg:h-[330px] bg-[#F1F1F1] rounded-[24px] p-6 lg:p-[32px]"
          >
            <img :src="quoteImg" alt="Quote" class="w-[30px] h-auto lg:w-[37px]" />

            <p
              class="mt-3 text-[15px] md:text-[16px] lg:text-[18px] font-semibold leading-[150%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif"
            >
              Great taste and very easy to consume. I feel more energetic and my skin has improved a
              lot. Will definitely buy again!
            </p>

            <div class="mt-6 lg:mt-[32px] border-t border-[#D8D8D8] pt-4">
              <h4
                class="text-[16px] lg:text-[18px] font-bold text-[#15213B]"
                style="font-family: 'Nunito', sans-serif"
              >
                Ankit Sharma
              </h4>

              <p
                class="mt-2 text-[15px] lg:text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif"
              >
                Delhi
              </p>
            </div>
          </div>

          <!-- Card 3 -->
          <div
            class="w-full md:col-span-2 lg:col-span-1 lg:w-[362.67px] min-h-[280px] lg:h-[330px] bg-[#F1F1F1] rounded-[24px] p-6 lg:p-[32px]"
          >
            <img :src="quoteImg" alt="Quote" class="w-[30px] h-auto lg:w-[37px]" />

            <p
              class="mt-3 text-[15px] md:text-[16px] lg:text-[18px] font-semibold leading-[150%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif"
            >
              Finally found a glutathione that actually works! My complexion is even and I feel so
              much better from inside.
            </p>

            <div class="mt-6 lg:mt-[32px] border-t border-[#D8D8D8] pt-4">
              <h4
                class="text-[16px] lg:text-[18px] font-bold text-[#15213B]"
                style="font-family: 'Nunito', sans-serif"
              >
                Neha Verma
              </h4>

              <p
                class="mt-2 text-[15px] lg:text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif"
              >
                Bangalore
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import badgeBorder from '@/assets/logo/border.png'
import badgeFill from '@/assets/logo/ocircle.png'
import quoteImg from '@/assets/icons/quote.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
```
