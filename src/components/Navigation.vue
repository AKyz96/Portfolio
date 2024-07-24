<script setup>
import Facebook from '@/components/icons/Facebook.vue'
import Linkedin from '@/components/icons/Linkedin.vue'
import Twitter from '@/components/icons/Twitter.vue'

defineProps({
  isActive: Boolean
})
</script>

<template>
  <header class="fixed width-[160px] top-0 bottom-0 pt-2.5 bg-[#222] overflow-auto z-11">
    <div class="relative mx-auto min-h-full pb-[50px] ">
      <div class="flex my-5 mx-auto max-w-[110px] justify-center z-0">
        <img src="../images/photo.jpg" alt="image" class="max-w-20">
      </div>

      <div class="relative z-1 mx-5 mt-5 mb-2.5 text-center">
        <div class="text-2xl fon-semibold text-[#f5f5f5]">Alex Smith</div>
      </div>

      <!-- Navigation -->
      <div class="pt-[25px] pb-10">
        <!-- Main menu -->
        <ul id="nav" class="font-normal font-sm text-[#f5f5f5] text-center cursor-pointer">
          <li class="border-y-[1px] border-[#333] px-10 py-2.5 hover:bg-[#333] hover:border-r-[1px] transition">
            <a href="#home">Home</a><!-- href value = data-id without # of .pt-page. -->
          </li>
          <li class="px-10 py-2.5 hover:bg-[#333] hover:border-r-[1px] transition">
            <a href="#about-me">About Me</a>
          </li>
          <li class="border-t-[1px] border-[#333] px-10 py-2.5 hover:bg-[#333] hover:border-r-[1px] transition">
            <a href="#resume">Resume</a>
          </li>
          <li class="border-t-[1px] border-[#333] px-10 py-2.5 hover:bg-[#333] hover:border-r-[1px] transition">
            <a href="#portfolio">Portfolio</a>
          </li>
          <li class="border-y-[1px] border-[#333] px-10 py-2.5 hover:bg-[#333] hover:border-r-[1px] transition">
            <a href="#contact">Contact</a>
          </li>
        </ul>
        <!-- /Main menu -->
      </div>
      <!-- Navigation -->

      <!-- Social Links -->
      <div class="inline-flex gap-1 justify-center w-full">
        <a href="#" class="w-[28px] h-[28px] text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition" target="_blank">
          <Twitter class="max-h-[15px] mx-auto"></Twitter>
        </a>
        <a href="#" class="w-[28px] h-[28px] text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition" target="_blank">
          <Linkedin class="max-h-[15px] mx-auto"></Linkedin>
        </a>
        <a href="#" class="w-[28px] h-[28px] text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition"
           target="_blank">
          <Facebook class="max-h-[15px] mx-auto"></Facebook>
        </a>
      </div>
      <!-- / Social Links -->

      <!-- Copyrights -->
      <div class="w-full absolute bottom-0 left-0 right-0 pt-[5px] px-2.5 pb-[15px] text-xs text-center text-[#aaa] ">© 2018 All rights reserved.</div>
      <!-- / Copyrights -->
    </div>
  </header>
  <!-- /Header -->

  <!-- Mobile Header -->
  <!--  <div class="mobile-header mobile-visible">-->
  <!--    <div class="mobile-logo-container">-->
  <!--      <div class="mobile-header-image">-->
  <!--        <a href="#">-->
  <!--          <img src="../images/photo.jpg" alt="image">-->
  <!--        </a>-->
  <!--      </div>-->
  <!--      <div class="mobile-site-title"><a href="#">Alex Smith</a></div>-->
  <!--    </div>-->

  <!--    <a class="menu-toggle mobile-visible">-->
  <!--      <i class="fa fa-bars"></i>-->
  <!--    </a>-->
  <!--  </div>-->
</template>