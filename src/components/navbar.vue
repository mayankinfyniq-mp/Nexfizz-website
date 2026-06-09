<template>
  <nav class="bg-white border-b border-gray-200">
    <div
      class="max-w-360 h-[80px] mx-auto px-12 md:px-14 lg:px-22 lg:py-2 flex items-center justify-between"
    >
      <div class="flex items-center">
        <img :src="logo" alt="Nexfiz Logo" class="h-6.25 lg:h-8.25 w-auto object-contain" />
      </div>
      <div class="hidden md:flex items-center gap-10 lg:gap-8">
        <a href="/" class="text-[#F47B63] font-medium text-lg hover:text-[#F47B63]"> Home </a>

        <a href="/products" class="text-[#1B2340] font-medium text-lg hover:text-[#F47B63]">
          Products
        </a>
        <a href="/about" class="text-[#1B2340] font-medium text-lg hover:text-[#F47B63]"> About </a>

        <a href="/faq" class="text-[#1B2340] font-medium text-lg hover:text-[#F47B63]"> FAQ </a>
        <button class="w-12 h-12 rounded-full bg-[#F7EAE8] flex items-center justify-center">
          <img :src="search" alt="Search" class="w-10 h-10" />
        </button>
        <button
          class="px-8 h-12 rounded-full bg-[#F47B63] text-white font-semibold hover:opacity-90 transition"
        >
          Contact Us
        </button>
      </div>
    </div>
  </nav>
</template>
<script setup>
import logo from '@/assets/logo/logo.png'
import search from '@/assets/icons/search.png'
</script>
