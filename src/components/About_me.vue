<script setup>
import Istore from '@/components/icons/Istore.vue'
import Icheckmark from '@/components/icons/Icheckmark.vue'
import Ilaptop from '@/components/icons/Ilaptop.vue'
import Ipencil from '@/components/icons/Ipencil.vue'
import Iflag from '@/components/icons/Iflag.vue'
import Ismile from '@/components/icons/Ismile.vue'
import Iclock from '@/components/icons/Iclock.vue'
import Icoffee from '@/components/icons/Icoffee.vue'
import Iarrow from '@/components/icons/Iarrow.vue'
</script>

<template>
  <section class="pt-[50px] pb-[70px] px-[70px] bg-[#222222] relative">
    <div class="text-[30px] font-semibold border-b-[2px] pb-4 border-[#666] text-[#f5f5f5]">
      About me
    </div>
    <div class="font-light flex flex-row-reverse w-full mt-2 text-[#bbb]">Artist, Thinker, Creative Doer</div>
    <div class="pt-10 flex gap-[30px]">
      <div class="w-1/2">
        <h2 class="font-semibold text-xl text-[#f5f5f5] pb-2.5">
          I am Web Designer @ Company.com
        </h2>
        <p class="text-[#d5d5d5] font-normal text-sm pb-2.5">
          Praesent ut tortor consectetur, semper sapien non, lacinia augue. Aenean arcu libero, facilisis et nisi non,
          tempus faucibus tortor. Mauris vel nulla aliquam, pellentesque enim ac, faucibus tortor. Nulla odio nibh,
          cursus sit amet urna id, dignissim euismod augue.
        </p>
        <p class="text-[#d5d5d5] font-normal text-sm pb-2.5">
          Duis sollicitudin, libero porttitor rutrum ultrices, turpis lorem fermentum justo, quis ornare augue tortor
          non est. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.
        </p>
      </div>
      <div>
        <ul class="gap-2 flex flex-col">
          <li><span
            class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Age</span><span>29</span>
          </li>
          <li><span
            class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Residence</span><span>USA</span>
          </li>
          <li><span class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Address</span><span>88 Some Street, Some Town</span>
          </li>
          <li><span class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">e-mail</span><span><a
            href="mailto:email@example.com" class="hover:underline">email@example.com</a></span></li>
          <li><span class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Phone</span><span><a
            href="tel:+0123123456789" class="hover:underline">+0123 123 456 789</a></span>
          </li>
          <li><span class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Skype</span><span>alex.smith</span>
          </li>
          <li><span
            class="font-semibold text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 mr-4">Freelance</span><span>Available</span>
          </li>
        </ul>
      </div>
    </div>
    <h2 class="text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 font-semibold text-xl text-[#f5f5f5] pt-[30px] inline-block ">
      What I Do
    </h2>
    <div class="flex gap-[30px]">
      <div class="pt-[15px] flex flex-col gap-5">
        <div class="flex gap-4">
          <Istore class="min-w-[42px] min-h-[42px]"></Istore>
          <div class="flex flex-col gap-2">
            <h2 class="font-semibold text-xl text-[#f5f5f5]">
              Ecommerce
            </h2>
            <p class="text-[#d5d5d5] font-normal text-sm">
              Pellentesque pellentesque, ipsum sit amet auctor accumsan, odio tortor bibendum massa, sit amet ultricies ex lectus scelerisque nibh. Ut non sodales odio.
            </p>
          </div>
        </div>
        <div class="flex gap-4">
          <Ilaptop class="min-w-[42px] min-h-[42px]"></Ilaptop>
          <div class="flex flex-col gap-2">
            <h2 class="font-semibold text-xl text-[#f5f5f5]">
              Web Design
            </h2>
            <p class="text-[#d5d5d5] font-normal text-sm">
              Pellentesque pellentesque, ipsum sit amet auctor accumsan, odio tortor bibendum massa, sit amet ultricies ex lectus scelerisque nibh. Ut non sodales odio.
            </p>
          </div>
        </div>
      </div>
      <div class="pt-[15px] flex flex-col gap-5">
        <div class="flex gap-4">
          <Ipencil class="min-w-[42px] min-h-[42px]"></Ipencil>
          <div class="flex flex-col gap-2">
            <h2 class="font-semibold text-xl text-[#f5f5f5]">
              Copywriter
            </h2>
            <p class="text-[#d5d5d5] font-normal text-sm">
              Pellentesque pellentesque, ipsum sit amet auctor accumsan, odio tortor bibendum massa, sit amet ultricies ex lectus scelerisque nibh. Ut non sodales odio.
            </p>
          </div>
        </div>
        <div class="flex gap-4">
          <Iflag class="min-w-[42px] min-h-[42px]"></Iflag>
          <div class="flex flex-col gap-2">
            <h2 class="font-semibold text-xl text-[#f5f5f5]">
              Management
            </h2>
            <p class="text-[#d5d5d5] font-normal text-sm">
              Pellentesque pellentesque, ipsum sit amet auctor accumsan, odio tortor bibendum massa, sit amet ultricies ex lectus scelerisque nibh. Ut non sodales odio.
            </p>
          </div>
        </div>
      </div>
    </div>
    <h2 class="text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 font-semibold text-xl text-[#f5f5f5] pt-[30px] inline-block ">
      Testimonials
    </h2>
    <div class="pt-5 flex gap-[30px]">
      <div class="relative w-1/2">
        <div class="px-4 py-5 bg-[#282828] border-[1px] border-[#444] rounded ml-12">
          <p class="italic text-[#d5d5d5]">
            Nam tempor commodo mi id sodales. Aenean sit amet nibh nec sapien consequat porta a sit amet diam.
          </p>
        </div>
        <div class="absolute top-[60px] w-20 rounded-full border-[1px] border-[#444]">
          <img src="@/images/testimonials/testimonial-2.jpg" alt="image" class="rounded-full">
        </div>
        <div class="pl-[92px] pt-3 flex flex-col">
          <p class="font-semibold text-[#f5f5f5] text-lg">Gary Johnson</p>
          <p class="text-[#aaa] text-xs">Locost Accessories</p>
        </div>
      </div>
      <div class="relative w-1/2">
        <div class="px-4 py-5 bg-[#282828] border-[1px] border-[#444] rounded ml-12">
          <p class="italic text-[#d5d5d5]">
            Donec eu est vel metus consequat volutpat. Nunc aliquet euismod mauris, a feugiat urna ullamcorper non.
          </p>
        </div>
        <div class="absolute top-[60px] w-20 rounded-full border-[1px] border-[#444]">
          <img src="@/images/testimonials/testimonial-2.jpg" alt="image" class="rounded-full">
        </div>
        <div class="pl-[92px] pt-3 flex flex-col">
          <p class="font-semibold text-[#f5f5f5] text-lg">Daniel Pringle</p>
          <p class="text-[#aaa] text-xs">Rolling Thunder</p>
        </div>
      </div>
      <div class="relative">
        <div class="absolute text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition right-[70px] bottom-0">
          <Iarrow class="rotate-90"></Iarrow>
        </div>
        <div class="absolute text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition right-[40px] bottom-0">
          <Iarrow class="rotate-[270deg]"></Iarrow>
        </div>
      </div>
    </div>
    <h2 class="text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 font-semibold text-xl text-[#f5f5f5] pt-[30px] inline-block ">
    Clients
    </h2>
    <div>
      <div class="pt-5 flex gap-[30px]">
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
        <div class="px-4 pb-4 w-1/6">
          <img src="@/images/clients/client-7.png" alt="image" class="max-w-[100px]">
        </div>
      </div>
      <div class="relative h-[36px]">
        <div class="absolute text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition right-[70px] bottom-0">
          <Iarrow class="rotate-90"></Iarrow>
        </div>
        <div class="absolute text-center bg-[#444] items-center flex opacity-80 hover:opacity-100 hover:bg-[#3E94E4] transition right-[40px] bottom-0">
          <Iarrow class="rotate-[270deg]"></Iarrow>
        </div>
      </div>
    </div>
    <h2 class="text-[#f5f5f5] border-b-[2px] border-[#0099e5] pb-1 font-semibold text-xl text-[#f5f5f5] pt-[30px] inline-block ">
      Fun Facts
    </h2>
    <div class="flex gap-[30px] pt-5">
      <div class="pt-5 pb-2.5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
        <Ismile class="w-[40px] h-[40px]"></Ismile>
        <h2 class="text-base text-[#f5f5f5] font-semibold">
          Happy Clients
        </h2>
        <span class="font-normal text-[#0099e5] text-3xl">
          2,325
        </span>
      </div>
      <div class="pt-5 pb-2.5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#444] border-[1px] border-[#333] w-full">
        <Iclock class="w-[40px] h-[40px]"></Iclock>
        <h2 class="text-base text-[#f5f5f5] font-semibold">
          Working Hours
        </h2>
        <span class="font-normal text-[#0099e5] text-3xl">
          7,582
        </span>
      </div>
      <div class="pt-5 pb-2.5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#333] border-[1px] border-[#444] w-full">
        <Icheckmark class="w-[40px] h-[40px]"></Icheckmark>
        <h2 class="text-base text-[#f5f5f5] font-semibold">
          Awards Won
        </h2>
        <span class="font-normal text-[#0099e5] text-3xl">
          12
        </span>
      </div>
      <div class="pt-5 pb-2.5 px-[15px] flex flex-col gap-2.5 items-center justify-center bg-[#444] border-[1px] border-[#333] w-full">
        <Icoffee class="w-[40px] h-[40px]"></Icoffee>
        <h2 class="text-base text-[#f5f5f5] font-semibold">
          Coffee Consumed
        </h2>
        <span class="font-normal text-[#0099e5] text-3xl">
          2,000
        </span>
      </div>
    </div>
  </section>
</template>