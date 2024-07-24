<script setup>
import Navigation from '@/components/Navigation.vue'
import Home from '@/components/Home.vue'
import About_me from '@/components/About_me.vue'
import Resume from '@/components/Resume.vue'
import Portfolio_block from '@/components/Portfolio_block.vue'
import Contact from '@/components/Contact.vue'
</script>

<template>
  <body class="text-sm font-normal text-[#d5d5d5] relative bg-[#000]">
  <Navigation></Navigation>
  <div class="pl-[160px] ml-5">
    <Home></Home>
    <About_me class="mt-3"></About_me>
    <Resume class="mt-3"></Resume>
    <Portfolio_block class="mt-3"></Portfolio_block>
    <Contact class="mt-3"></Contact>
  </div>
  </body>
</template>
