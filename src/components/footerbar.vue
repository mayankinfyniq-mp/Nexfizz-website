<template>
  <section class="w-full bg-[#FEF2F4] overflow-hidden">
    <!-- ================= MOBILE / TABLET ================= -->
    <div class="lg:hidden bg-[#13224A]">
      <div class="px-5 py-6">
        <!-- Newsletter -->
        <div class="bg-[#F7F7F7] rounded-[24px] p-5">
          <div
            class="inline-flex px-4 py-2 rounded-full bg-[#FCE7E2] text-[#F47C62] text-xs font-bold"
          >
            Join 50,000+ Wellness Enthusiasts
          </div>

          <h2
            class="mt-4 text-[#15213B] text-[32px] leading-[120%] font-extrabold"
            style="font-family: 'Nunito', sans-serif"
          >
            Get Exclusive Wellness Deals
          </h2>

          <p
            class="mt-4 text-[#505050] text-sm leading-[160%]"
            style="font-family: 'Manrope', sans-serif"
          >
            Subscribe for early access to new products, health tips and exclusive discounts.
          </p>

          <div class="mt-6">
            <h3 class="text-[#15213B] font-bold text-lg">Join Newsletter</h3>

            <div class="mt-4 flex flex-col gap-3">
              <input
                type="email"
                placeholder="Enter your email"
                class="h-12 rounded-full bg-[#EFEFEF] px-5 outline-none"
              />

              <button class="h-12 rounded-full bg-[#F47C62] text-white font-bold">Subscribe</button>
            </div>
          </div>

          <div class="mt-6 flex flex-col gap-3">
            <div class="flex items-center gap-2">
              <img :src="tickIcon" class="w-4 h-4" />
              <span class="text-[#15213B]">Free Wellness Tips</span>
            </div>

            <div class="flex items-center gap-2">
              <img :src="tickIcon" class="w-4 h-4" />
              <span class="text-[#15213B]">Exclusive Discounts</span>
            </div>

            <div class="flex items-center gap-2">
              <img :src="tickIcon" class="w-4 h-4" />
              <span class="text-[#15213B]">New Product Alerts</span>
            </div>
          </div>
        </div>

        <!-- Footer -->
        <div class="mt-10 text-white">
          <!-- Logo -->
          <div class="flex items-center gap-3">
            <img :src="logo" class="w-10 h-10 object-contain" />
            <img :src="logo1" class="h-[28px] object-contain" />
          </div>

          <p class="mt-6 text-white/70 leading-[170%]" style="font-family: 'Nunito', sans-serif">
            The Next Level Fizz. Premium effervescent supplements that taste amazing and work
            faster. 100% Sugar-Free, Vegetarian & Made in India with love.
          </p>

          <!-- Certifications -->
          <div class="mt-6 flex flex-wrap gap-4">
            <div class="flex items-center gap-2">
              <img :src="gmpIcon" class="w-4 h-4" />
              <span class="text-sm">GMP Certified</span>
            </div>

            <div class="flex items-center gap-2">
              <img :src="vegIcon" class="w-4 h-4" />
              <span class="text-sm">100% Vegetarian</span>
            </div>

            <div class="flex items-center gap-2">
              <img :src="fssaiIcon" class="w-4 h-4" />
              <span class="text-sm">FSSAI Approved</span>
            </div>
          </div>

          <!-- Social -->
          <div class="mt-8 flex gap-5">
            <img :src="facebookIcon" class="w-5 h-5" />
            <img :src="instagramIcon" class="w-5 h-5" />
            <img :src="twitterIcon" class="w-5 h-5" />
            <img :src="youtubeIcon" class="w-5 h-5" />
            <img :src="linkedinIcon" class="w-5 h-5" />
          </div>

          <!-- Products -->
          <div class="mt-10">
            <h4 class="font-bold text-lg">Products</h4>

            <div class="mt-4 flex flex-col gap-3 text-white/70">
              <span>Apple Cider Vinegar</span>
              <span>Electrolyte</span>
              <span>Glutathione</span>
              <span>Multivitamins</span>
              <span>Amla Zinc</span>
            </div>
          </div>

          <!-- Company -->
          <div class="mt-10">
            <h4 class="font-bold text-lg">Company</h4>

            <div class="mt-4 flex flex-col gap-3 text-white/70">
              <span>About Us</span>
              <span>Our Products</span>
              <span>FAQ</span>
              <span>Contact Us</span>
            </div>
          </div>

          <!-- Contact -->
          <div class="mt-10">
            <h4 class="font-bold text-lg">Contact</h4>

            <div class="mt-4 flex flex-col gap-5 text-white/70">
              <div class="flex gap-3">
                <img :src="locationIcon" class="w-5 h-5 mt-1" />
                <span>
                  Unitrade Nexus Nutrascience<br />
                  Ahmedabad, Gujarat, India
                </span>
              </div>

              <div class="flex gap-3">
                <img :src="phoneIcon" class="w-5 h-5 mt-1" />
                <span>
                  (+91) 9408516466<br />
                  9429761637
                </span>
              </div>

              <div class="flex gap-3">
                <img :src="mailIcon" class="w-5 h-5 mt-1" />
                <span>info@unitradenexus.com</span>
              </div>
            </div>
          </div>

          <div class="mt-10 border-t border-white/10 pt-6">
            <p class="text-white/50 text-sm">© 2026 NexFiz by Unitrade Nexus Nutrascience.</p>

            <div class="mt-4 flex flex-col gap-2 text-white/50 text-sm">
              <span>Privacy Policy</span>
              <span>Terms of Service</span>
              <span>Return Policy</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- ================= DESKTOP ================= -->
    <div class="hidden lg:block">
      <section class="w-full bg-[#FEF2F4] overflow-hidden">
        <div class="relative mx-auto max-w-[1440px] h-[749px]">
          <!-- Blue Footer Background -->
          <div class="absolute bottom-0 left-0 w-full h-[561px] bg-[#13224A]"></div>

          <!-- Newsletter Card -->
          <div
            class="absolute left-1/2 -translate-x-1/2 top-0 w-[1264px] h-[332px] bg-[#F7F7F7] rounded-[32px] px-[68px] py-[56px] box-border"
          >
            <div class="flex justify-between">
              <!-- Left -->
              <div class="max-w-[620px]">
                <div class="inline-flex px-[20px] py-[10px] rounded-full bg-[#FCE7E2]">
                  <span
                    class="text-[#F47C62] text-[16px] font-extrabold"
                    style="font-family: 'Manrope', sans-serif; font-weight: 700"
                  >
                    Join 50,000+ Wellness Enthusiasts
                  </span>
                </div>

                <h2
                  class="mt-[24px] text-[38px] leading-[120%] font-extrabold text-[#15213B]"
                  style="font-family: 'Nunito', sans-serif; font-weight: 800"
                >
                  Get Exclusive Wellness Deals
                </h2>

                <p
                  class="mt-[20px] text-[16px] leading-[150%] text-[#505050]"
                  style="font-family: 'Manrope', sans-serif; font-weight: 600"
                >
                  Subscribe for early access to new products, health tips, and exclusive discounts.
                  No spam, unsubscribe anytime.
                </p>
              </div>

              <!-- Right -->
              <div class="w-[500px] pt-[44px]">
                <h3
                  class="text-[20px] font-bold text-[#15213B]"
                  style="font-style: 'Nunito', sans-serif; font-weight: 700"
                >
                  Join Newsletter
                </h3>

                <div class="mt-[20px] flex gap-[20px]">
                  <input
                    type="email"
                    placeholder="Enter your email"
                    class="w-[303px] h-[56px] rounded-full bg-[#EFEFEF] px-[28px] outline-none"
                  />

                  <button
                    class="w-[136px] h-[56px] rounded-full bg-[#F47C62] text-white font-extrabold"
                    style="font-style: 'Nunito', sans-serif; font-weight: 800"
                  >
                    Subscribe
                  </button>
                </div>
              </div>
            </div>

            <!-- Features -->
            <div class="mt-[48px] flex gap-[56px]">
              <div class="flex items-center gap-3">
                <img :src="tickIcon" class="w-[16.67px] h-[16.67px]" />
                <span
                  class="text-[18px] text-[#15213B] font-semibold"
                  style="font-style: 'Nunito', sans-serif; font-weight: 600"
                >
                  Free Wellness Tips
                </span>
              </div>

              <div class="flex items-center gap-3">
                <img :src="tickIcon" class="w-6 h-6" />
                <span
                  class="text-[18px] text-[#15213B] font-semibold"
                  style="font-style: 'Nunito', sans-serif; font-weight: 600"
                >
                  Exclusive Discounts
                </span>
              </div>

              <div class="flex items-center gap-3">
                <img :src="tickIcon" class="w-6 h-6" />
                <span
                  class="text-[18px] text-[#15213B] font-semibold"
                  style="font-style: 'Nunito', sans-serif; font-weight: 600"
                >
                  New Product Alerts
                </span>
              </div>
            </div>
          </div>

          <!-- Footer Content -->
          <div
            class="absolute left-0 bottom-0 w-full h-[561px] pt-[180px] px-[88px] box-border text-white"
          >
            <div class="flex justify-between">
              <!-- Company -->
              <div class="w-[450px]">
                <div class="flex items-center gap-3">
                  <img :src="logo" class="h-[40px] w-[40px]" />
                  <img :src="logo1" class="h-[28px] object-contain" />
                </div>

                <p
                  class="mt-[28px] text-[14px] leading-[170%] text-white/70"
                  style="font-style: 'Nunito', sans-serif; font-weight: 400"
                >
                  The Next Level Fizz. Premium effervescent supplements that taste amazing and work
                  faster. 100% Sugar-Free, Vegetarian & Made in India with love.
                </p>

                <!-- Certifications -->
                <div class="mt-[28px] flex gap-[28px]">
                  <div class="flex items-center gap-2">
                    <img :src="gmpIcon" class="w-[16px] h-[16px]" />
                    <span class="text-white/70 text-[12px]">GMP Certified</span>
                  </div>

                  <div class="flex items-center gap-2">
                    <img :src="vegIcon" class="w-[16px] h-[16px]" />
                    <span class="text-white/70 text-[12px]">100% Vegetarian</span>
                  </div>

                  <div class="flex items-center gap-2">
                    <img :src="fssaiIcon" class="w-[16px] h-[16px]" />
                    <span class="text-white/70 text-[12px]">FSSAI Approved</span>
                  </div>
                </div>

                <!-- Social -->
                <div class="mt-[32px] flex gap-4">
                  <img :src="facebookIcon" class="w-[20px] h-[20px]" />
                  <img :src="instagramIcon" class="w-[20px] h-[20px]" />
                  <img :src="twitterIcon" class="w-[20px] h-[20px]" />
                  <img :src="youtubeIcon" class="w-[20px] h-[20px]" />
                  <img :src="linkedinIcon" class="w-[20px] h-[20px]" />
                </div>
              </div>

              <!-- Products -->
              <div>
                <h4 class="font-extrabold text-[16px]">Products</h4>

                <div class="mt-6 flex flex-col gap-4 text-white/70">
                  <span>Apple Cider Vinegar</span>
                  <span>Electrolyte</span>
                  <span>Glutathione</span>
                  <span>Multivitamins</span>
                  <span>Amla Zinc</span>
                </div>
              </div>

              <!-- Company -->
              <div>
                <h4 class="font-extrabold text-[16px]">Company</h4>

                <div class="mt-6 flex flex-col gap-4 text-white/70">
                  <span>About Us</span>
                  <span>Our Products</span>
                  <span>FAQ</span>
                  <span>Contact Us</span>
                </div>
              </div>

              <!-- Contact -->
              <div class="w-[320px]">
                <h4 class="font-extrabold text-[16px]">Contact</h4>

                <div class="mt-6 flex flex-col gap-6 text-white/70">
                  <div class="flex gap-4">
                    <img :src="locationIcon" class="w-6 h-6" />
                    <span>
                      Unitrade Nexus Nutrascience<br />
                      Ahmedabad, Gujarat, India
                    </span>
                  </div>

                  <div class="flex gap-4">
                    <img :src="phoneIcon" class="w-6 h-6" />
                    <span>
                      (+91) 9408516466<br />
                      9429761637
                    </span>
                  </div>

                  <div class="flex gap-4">
                    <img :src="mailIcon" class="w-6 h-6" />
                    <span> info@unitradenexus.com </span>
                  </div>
                </div>
              </div>
            </div>

            <!-- Bottom Line -->
            <div class="mt-[48px] border-t border-white/10 pt-[28px] flex justify-between">
              <span class="text-white/50">
                © 2026 NexFiz by Unitrade Nexus Nutrascience All rights reserved.
              </span>

              <div class="flex gap-10 text-white/50">
                <span>Privacy Policy</span>
                <span>Terms of Service</span>
                <span>Return Policy</span>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </section>
</template>
<script setup>
import logo from '@/assets/logo/logo1.png'
import logo1 from '@/assets/logo/logoname.png'
import gmpIcon from '@/assets/icons/gmp.png'
import vegIcon from '@/assets/icons/veg.png'
import fssaiIcon from '@/assets/icons/fssai.png'
import facebookIcon from '@/assets/icons/facebook.png'
import instagramIcon from '@/assets/icons/instagram.png'
import twitterIcon from '@/assets/icons/twitter.png'
import youtubeIcon from '@/assets/icons/youtube.png'
import linkedinIcon from '@/assets/icons/linkedin.png'
import locationIcon from '@/assets/icons/location.png'
import phoneIcon from '@/assets/icons/phone.png'
import mailIcon from '@/assets/icons/mail.png'
import tickIcon from '@/assets/icons/tick1.png'
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
</style>
