<script setup>
import Imap from '@/components/icons/Imap.vue'
import Iphone from '@/components/icons/Iphone.vue'
import Icheckmark from '@/components/icons/Icheckmark.vue'
import Ienvelope from '@/components/icons/Ienvelope.vue'
</script>

<template>
  <section class="pt-[50px] pb-[70px] px-[70px] bg-[#222222] relative">
    <div class="text-[30px] font-semibold border-b-[2px] pb-4 border-[#666] text-[#f5f5f5]">
      Contact
    </div>
    <div class="font-light flex flex-row-reverse w-full mt-2 text-[#bbb]">Get in Touch</div>
    <div>
      <div class="flex gap-[30px] pt-10">
        <div
          class="pt-5 pb-5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
          <Iphone class="w-[40px] h-[40px]"></Iphone>
          <span class="font-semibold text-[#f5f5f5] text-base">
          415-832-2000
        </span>
        </div>
        <div
          class="pt-5 pb-5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
          <Imap class="w-[40px] h-[40px]"></Imap>
          <span class="font-semibold text-[#f5f5f5] text-base">
          San Francisco
        </span>
        </div>
        <div
          class="pt-5 pb-5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
          <Ienvelope class="w-[40px] h-[40px]"></Ienvelope>
          <span class="font-semibold text-[#f5f5f5] text-base">
          alex@example.com
        </span>
        </div>
        <div
          class="pt-5 pb-5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
          <Icheckmark class="w-[40px] h-[40px]"></Icheckmark>
          <span class="font-semibold text-[#f5f5f5] text-base">
          Freelance Available
        </span>
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center">
      <h2 class="text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 font-semibold text-xl text-[#f5f5f5] pt-[30px] inline-block items-start">
        How Can I Help You?
      </h2>
      <div class="flex w-2/3 mt-5 gap-4">
        <div class="flex flex-col w-full gap-4">
          <input type="text" class="bg-[#222222] py-2.5 pl-3 pr-6 border-[#555] border-[1px] outline-none" placeholder="Full Name">
          <input type="email" class="bg-[#222222] py-2.5 pl-3 pr-6 border-[#555] border-[1px] outline-none" placeholder="Email Address">
          <input type="text" class="bg-[#222222] py-2.5 pl-3 pr-6 border-[#555] border-[1px] outline-none" placeholder="Subject">
        </div>
        <textarea class="bg-[#222222] py-2.5 pl-3 pr-6 border-[#555] border-[1px] outline-none resize-none w-full" placeholder="Message"></textarea>
      </div>
      <div class="mt-[60px] inline-block">
        <a href="#" class="cursor-pointer text-[#fff] border-[2px] hover:bg-[#0099e5] transition py-3 px-7 border-[#0099e5]">
          Send message
        </a>
      </div>
    </div>
  </section>
</template>
