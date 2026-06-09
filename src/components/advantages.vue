<template>
  <section class="w-full bg-[#FEF2F4] overflow-hidden">
    <div class="mx-auto max-w-[1440px] h-[1698px] px-6 md:px-10 lg:px-[88px] py-16 lg:py-[112px]">
      <div class="grid grid-cols-1 lg:grid-cols-[380px_1fr] gap-12 lg:gap-[80px]">
        <!-- Left Content -->
        <div class="w-[443px] h-[279px]">
          <h2
            class="text-[#15213B] max-w-[412px] h-[84px] font-extrabold uppercase text-[24px] md:text-[28px] lg:text-[30px] leading-[120%]"
            style="font-family: 'Nunito', sans-serif"
          >
            FIND THE RIGHT <br />
            WELLNESS SUPPORT
          </h2>

          <p
            class="mt-6 max-w-[445px] h-[44px] text-[#15213B] text-[16px] leading-[150%]"
            style="font-family: 'Manrope', sans-serif"
          >
            Discover fizzy daily supplements designed to support your body, mind, and lifestyle.
          </p>
        </div>

        <!-- Cards -->
        <div class="flex flex-col gap-8 lg:gap-10 lg:pl-[88px]">
          <!-- Hydration -->
          <div
            class="relative max-w-[666px] h-[180px] md:h-[220px] lg:h-[250px] rounded-[24px] lg:rounded-[32px] overflow-hidden"
          >
            <img
              :src="hydrationBg"
              alt="Hydration"
              class="absolute inset-0 w-full h-full object-cover"
            />

            <div
              class="relative z-10 h-full flex items-center justify-between px-6 md:px-8 lg:px-[40px] lg:py-[40px]"
            >
              <div>
                <h3
                  class="font-extrabold text-[#15213B] text-[16px] md:text-[28px] lg:text-[35px]"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Hydration
                </h3>

                <p
                  class="mt-2 text-[#15213B] text-[10px] md:text-[12px] lg:text-[16px]"
                  style="font-family: 'Manrope', sans-serif"
                >
                  Stay refreshed all day
                </p>
              </div>

              <button
                class="w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14 rounded-full bg-white flex items-center justify-center text-[24px] lg:text-[36px]"
              >
                <img :src="arrowImg" alt="Arrow" class="w-[24.37px] h-[17.78px] object-contain" />
              </button>
            </div>
          </div>

          <!-- Skin Glow -->
          <div
            class="relative max-w-[666px] h-[180px] md:h-[220px] lg:h-[250px] rounded-[24px] lg:rounded-[32px] overflow-hidden"
          >
            <img
              :src="skinGlowBg"
              alt="Skin Glow"
              class="absolute inset-0 w-full h-full object-cover"
            />

            <div
              class="relative z-10 h-full flex items-center justify-between px-6 md:px-8 lg:px-[40px] lg:py-[40px]"
            >
              <div>
                <h3
                  class="font-extrabold text-[#15213B] text-[16px] md:text-[28px] lg:text-[35px]"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Skin Glow
                </h3>

                <p
                  class="mt-2 text-[#15213B] text-[10px] md:text-[12px] lg:text-[16px]"
                  style="font-family: 'Manrope', sans-serif"
                >
                  Radiate from within
                </p>
              </div>

              <button
                class="w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14 rounded-full bg-white flex items-center justify-center text-[24px] lg:text-[36px]"
              >
                <img :src="arrowImg" alt="Arrow" class="w-[24.37px] h-[17.78px] object-contain" />
              </button>
            </div>
          </div>

          <!-- Weight Management -->
          <div
            class="relative max-w-[666px] h-[180px] md:h-[220px] lg:h-[250px] rounded-[24px] lg:rounded-[32px] overflow-hidden"
          >
            <img
              :src="weightBg"
              alt="Weight Management"
              class="absolute inset-0 w-full h-full object-cover"
            />

            <div
              class="relative z-10 h-full flex items-center justify-between px-6 md:px-8 lg:px-[40px] lg:py-[40px]"
            >
              <div>
                <h3
                  class="font-extrabold text-[#15213B] text-[16px] md:text-[28px] lg:text-[35px]"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Weight Management
                </h3>

                <p
                  class="mt-2 text-[#15213B] text-[10px] md:text-[12px] lg:text-[16px]"
                  style="font-family: 'Manrope', sans-serif"
                >
                  Smart wellness support
                </p>
              </div>

              <button
                class="w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14 rounded-full bg-white flex items-center justify-center text-[24px] lg:text-[36px]"
              >
                <img :src="arrowImg" alt="Arrow" class="w-[24.37px] h-[17.78px] object-contain" />
              </button>
            </div>
          </div>

          <!-- Immunity -->
          <div
            class="relative max-w-[666px] h-[180px] md:h-[220px] lg:h-[250px] rounded-[24px] lg:rounded-[32px] overflow-hidden"
          >
            <img
              :src="immunityBg"
              alt="Immunity"
              class="absolute inset-0 w-full h-full object-cover"
            />

            <div
              class="relative z-10 h-full flex items-center justify-between px-6 md:px-8 lg:px-[40px] lg:py-[40px]"
            >
              <div>
                <h3
                  class="font-extrabold text-[#15213B] text-[16px] md:text-[28px] lg:text-[35px]"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Immunity
                </h3>

                <p
                  class="mt-2 text-[#15213B] text-[10px] md:text-[12px] lg:text-[16px]"
                  style="font-family: 'Manrope', sans-serif"
                >
                  Strengthen your defense
                </p>
              </div>

              <button
                class="w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14 rounded-full bg-white flex items-center justify-center text-[24px] lg:text-[36px]"
              >
                <img :src="arrowImg" alt="Arrow" class="w-[24.37px] h-[17.78px] object-contain" />
              </button>
            </div>
          </div>

          <!-- Daily Wellness -->
          <div
            class="relative max-w-[666px] h-[180px] md:h-[220px] lg:h-[250px] rounded-[24px] lg:rounded-[32px] overflow-hidden"
          >
            <img
              :src="dailyWellnessBg"
              alt="Daily Wellness"
              class="absolute inset-0 w-full h-full object-cover"
            />

            <div
              class="relative z-10 h-full flex items-center justify-between px-6 md:px-8 lg:px-[40px] lg:py-[40px]"
            >
              <div>
                <h3
                  class="font-extrabold text-[#15213B] text-[16px] md:text-[28px] lg:text-[35px]"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Daily Wellness
                </h3>

                <p
                  class="mt-2 text-[#15213B] text-[10px] md:text-[12px] lg:text-[16px]"
                  style="font-family: 'Manrope', sans-serif"
                >
                  Complete nutrition
                </p>
              </div>

              <button
                class="w-10 h-10 md:w-12 md:h-16 lg:w-14 lg:h-14 rounded-full bg-white flex items-center justify-center text-[24px] lg:text-[36px]"
              >
                <img :src="arrowImg" alt="Arrow" class="w-[24.37px] h-[17.78px] object-contain" />
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import hydrationBg from '@/assets/background/hydration-bg.png'
import skinGlowBg from '@/assets/background/skin-glow-bg.png'
import weightBg from '@/assets/background/weight-bg.png'
import immunityBg from '@/assets/background/immunity-bg.png'
import dailyWellnessBg from '@/assets/background/daily-wellness-bg.png'
import arrowImg from '@/assets/icons/arrow.png'
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
