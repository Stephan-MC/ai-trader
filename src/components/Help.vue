<template>
  <section class="py-32 max-md:px-4">
    <div class="md:container mx-auto text-left">
      <h4 class="text-transparent from-blue-500 to-emrald-500 bg-gradient-to-tr bg-clip-text uppercase font-semibold tracking-wide">Always Here to help</h4>
      <h3 class="text-4xl my-5 font-bold">24/7 expert support</h3>

      <div class="flex flex-col gap-6 mt-20">
        <p class="">
          <span class="font-bold">All plans and services included</span>
          <span class="text-gray-600/90"> No matter which subscription you choose, we believe our entire community deserves support every second, 365 days a year.</span>
        </p>
        <p class="">
          <span class="font-bold">97% satisfaction</span>
          <span class="text-gray-600/90"> We are always there for you when you need us and are committed to ensuring our customer satisfaction rate is as close to 100% as possible</span>
        </p>
      </div>

      <div class="px-6 lg:px-0 mt-32">
        <div class="relative isolate bg-gradient-to-tr from-blue-600 to-emerald-600 pt-16 mx-auto sm:max-w-2xl rounded-3xl pl-8 sm:pl-10 lg:mx-0 lg:max-w-none mt-14">
         <div class="absolute w-full h-full top-0 left-0 rounded-3xl overflow-hidden">
          <div class="absolute -inset-y-px -left-3 -z-10 w-full origin-bottom-left skew-x-[-30deg] bg-emerald-100 opacity-20 ring-1 ring-inset ring-white" aria-hidden="true"></div>
         </div>
         <div class="mx-auto max-w-2xl sm:mx-0 sm:max-w-none"><picture>
           <img class="-mt-36 w-full max-w-none rounded-br-3xl relative z-20 lazyloaded" :src="support" alt="" data-eio="p" decoding="async" width="1000" height="874">
          </picture>
         </div>
         <div class="pointer-events-none absolute inset-0 ring-1 ring-inset ring-black/10 rounded-3xl" aria-hidden="true"></div>
        </div>
       </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import support from '../assets/support02.png'
</script>

<style scoped>

</style>
