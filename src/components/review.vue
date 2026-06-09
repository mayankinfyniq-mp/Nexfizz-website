<template>
  <section class="w-full bg-[#FEF2F4] overflow-hidden">
    <!-- Background Layout -->
    <div
      class="mx-auto max-w-[1440px] h-[828px] pt-[152px] pr-[88px] pb-[112px] pl-[88px] box-border"
    >
      <!-- White Container -->
      <div class="relative w-[1264px] h-[564px] bg-[#F7F7F7] rounded-[24px] p-[56px] box-border">
        <!-- Satisfaction Badge -->
        <div class="absolute top-[-52px] right-[128px] w-[187.08px] h-[187.72px] rotate-[13.3deg]">
          <!-- Border Image -->
          <img :src="badgeBorder" alt="" class="absolute inset-0 w-full h-full object-contain" />

          <!-- Fill Image -->
          <img
            :src="badgeFill"
            alt=""
            class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 w-[142.37px] h-[143.73px] object-contain"
          />

          <!-- Badge Text -->
          <div class="absolute inset-0 flex flex-col items-center justify-center text-white">
            <div
              class="text-[48px] font-extrabold leading-none"
              style="font-family: 'Nunito', sans-serif"
            >
              100%
            </div>

            <div
              class="text-[21.5px] uppercase font-extrabold"
              style="font-family: 'Nunito', sans-serif; font-weight: 800"
            >
              Satisfied
            </div>
          </div>
        </div>

        <!-- Header Section -->
        <div>
          <h2
            class="text-[#15213B] text-[32px] leading-[120%] font-extrabold"
            style="font-family: 'Nunito', sans-serif"
          >
            What Our Customers Say
          </h2>

          <p
            class="mt-[16px] text-[17px] leading-[150%] text-[#505050]"
            style="font-family: 'Manrope', sans-serif"
          >
            Join thousands of happy customers who've made NexFiz part of their daily wellness
            routine
          </p>
        </div>

        <!-- Testimonial Cards -->
        <div class="mt-[40px] flex gap-[40px]">
          <!-- Card 1 -->
          <div class="w-[362.67px] h-[330px] bg-[#F1F1F1] rounded-[24px] p-[32px] box-border">
            <img :src="quoteImg" alt="Quote" class="w-[37px] h-[28px] object-contain" />

            <p
              class="mt-[8px] text-[18px] font-semibold leading-[150%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif; font-weight: 600"
            >
              I've been using NexFiz Glutathione for a month now and my skin looks brighter and more
              radiant. Absolutely love the strawberry flavor!
            </p>

            <div
              class="mt-[32px] w-[298.67px] h-[71px] border-t border-[#D8D8D8] pt-[16px] box-border"
            >
              <h4
                class="text-[18px] font-bold text-[#15213B] leading-none"
                style="font-family: 'Nunito', sans-serif; font-weight: 800"
              >
                Priya Sharma
              </h4>

              <p
                class="mt-[8px] text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif; font-weight: 600"
              >
                Mumbai
              </p>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="w-[362.67px] h-[330px] bg-[#F1F1F1] rounded-[24px] p-[32px] box-border">
            <img :src="quoteImg" alt="Quote" class="w-[37px] h-[28px] object-contain" />

            <p
              class="mt-[8px] text-[18px] font-semibold leading-[160%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif; font-weight: 600"
            >
              Great taste and very easy to consume. I feel more energetic and my skin has improved a
              lot. Will definitely buy again!
            </p>

            <div
              class="mt-[32px] w-[298.67px] h-[71px] border-t border-[#D8D8D8] pt-[16px] box-border"
            >
              <h4
                class="text-[18px] font-bold text-[#15213B] leading-none"
                style="font-family: 'Nunito', sans-serif; font-weight: 800"
              >
                Ankit Sharma
              </h4>

              <p
                class="mt-[8px] text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif; font-weight: 600"
              >
                Delhi
              </p>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="w-[362.67px] h-[330px] bg-[#F1F1F1] rounded-[24px] p-[32px] box-border">
            <img :src="quoteImg" alt="Quote" class="w-[37px] h-[28px] object-contain" />

            <p
              class="mt-[8px] text-[18px] font-semibold leading-[160%] text-[#15213B]"
              style="font-family: 'Nunito', sans-serif; font-weight: 600"
            >
              Finally found a glutathione that actually works! My complexion is even and I feel so
              much better from inside.
            </p>

            <div
              class="mt-[32px] w-[298.67px] h-[71px] border-t border-[#D8D8D8] pt-[16px] box-border"
            >
              <h4
                class="text-[18px] font-bold text-[#15213B] leading-none"
                style="font-family: 'Nunito', sans-serif; font-weight: 800"
              >
                Neha Verma
              </h4>

              <p
                class="mt-[8px] text-[18px] font-semibold text-[#15213B]"
                style="font-family: 'Manrope', sans-serif; font-weight: 600"
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
