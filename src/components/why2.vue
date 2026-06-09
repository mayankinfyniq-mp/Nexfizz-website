```vue
<template>
  <section class="w-full bg-[#8E1455] overflow-hidden">
    <div
      class="mx-auto max-w-[1440px] min-h-[500px] lg:h-[618px] flex items-center justify-center lg:justify-between px-6 md:px-10 lg:px-[48px] py-12 lg:py-0"
    >
      <!-- Left Image (Only Desktop) -->
      <div class="hidden lg:flex relative shrink-0 max-w-[648px] justify-end">
        <img
          :src="why2bg"
          alt="Why Effervescent"
          class="w-full max-w-[648px] h-[616px] object-cover"
        />

        <!-- Gradient Overlay -->
        <div
          class="absolute top-0 right-0 z-10 w-[123px] h-[616px]"
          style="background: linear-gradient(90deg, rgba(142, 20, 85, 0) 0%, #8e1455 100%)"
        ></div>
      </div>

      <!-- Right Content -->
      <div class="w-full lg:h-[616px] flex items-center justify-center lg:justify-end">
        <div class="w-full max-w-[556px] lg:h-[394px] lg:pr-[88px]">
          <!-- Heading -->
          <h2
            class="w-full lg:w-[556px] font-extrabold text-[28px] md:text-[32px] lg:text-[40px] leading-[110%] text-white"
            style="font-family: 'Nunito', sans-serif"
          >
            Why Effervescent is Better?
          </h2>

          <!-- Features Container -->
          <div class="mt-10 lg:mt-[56px] w-full lg:w-[556px] flex flex-col gap-6">
            <!-- Feature 1 -->
            <div class="flex gap-4 lg:gap-6">
              <div
                class="w-[56px] h-[56px] lg:w-[66px] lg:h-[66px] rounded-full bg-white/10 flex items-center justify-center shrink-0"
              >
                <img
                  :src="tickImg"
                  alt="Tick"
                  class="w-[22px] lg:w-[25.77px] h-auto object-contain"
                />
              </div>

              <div>
                <h3
                  class="font-extrabold text-[20px] lg:text-[22px] text-white"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Faster Absorption
                </h3>

                <p
                  class="mt-[6px] text-[14px] lg:text-[16px] text-white/80"
                  style="font-family: 'Manrope', sans-serif; font-weight: 600"
                >
                  Quick nutrient release for better results
                </p>
              </div>
            </div>

            <!-- Feature 2 -->
            <div class="flex gap-4 lg:gap-6">
              <div
                class="w-[56px] h-[56px] lg:w-[66px] lg:h-[66px] rounded-full bg-white/10 flex items-center justify-center shrink-0"
              >
                <img
                  :src="tickImg"
                  alt="Tick"
                  class="w-[22px] lg:w-[25.77px] h-auto object-contain"
                />
              </div>

              <div>
                <h3
                  class="font-extrabold text-[20px] lg:text-[22px] text-white"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Higher Bioavailability
                </h3>

                <p
                  class="mt-[6px] text-[14px] lg:text-[16px] text-white/80"
                  style="font-family: 'Manrope', sans-serif; font-weight: 600"
                >
                  Better absorption compared to regular tablets
                </p>
              </div>
            </div>

            <!-- Feature 3 -->
            <div class="flex gap-4 lg:gap-6">
              <div
                class="w-[56px] h-[56px] lg:w-[66px] lg:h-[66px] rounded-full bg-white/10 flex items-center justify-center shrink-0"
              >
                <img
                  :src="tickImg"
                  alt="Tick"
                  class="w-[22px] lg:w-[25.77px] h-auto object-contain"
                />
              </div>

              <div>
                <h3
                  class="font-extrabold text-[20px] lg:text-[22px] text-white"
                  style="font-family: 'Nunito', sans-serif"
                >
                  Great Taste
                </h3>

                <p
                  class="mt-[6px] text-[14px] lg:text-[16px] text-white/80"
                  style="font-family: 'Manrope', sans-serif; font-weight: 600"
                >
                  Delicious fizzy drink you'll look forward to
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import why2bg from '@/assets/background/why2bg.png'
import tickImg from '@/assets/icons/tick.png'
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
```
