<template>
    
  <section
  class="relative h-screen flex items-center justify-center bg-cover bg-center"
  :style="{ backgroundImage: `url(${bgImage})` }"
>
  <!-- Gradient Overlay -->
  <div class="absolute inset-0 bg-gradient-to-br from-black/70 via-black/50 to-transparent"></div>

  <!-- Hero Content Card -->
  <div class="relative z-10 text-white px-4 md:px-8 max-w-3xl text-center backdrop-blur-md bg-white/10 rounded-xl shadow-xl py-12">
    <h1 class="text-4xl md:text-5xl font-extrabold leading-tight mb-4">
      Best Lighting Services in Sikar | City Lights Sikar
    </h1>

    <p class="text-lg md:text-xl mb-6 text-gray-200">
      We provide premium wedding lighting in Sikar, event decoration in Sikar,
      LED lights, chandeliers, and complete lighting solutions for homes and events.
    </p>

    <h2 class="text-xl md:text-2xl font-semibold mb-6">
      Trusted Lighting & Wedding Decoration Services in Sikar Rajasthan
    </h2>

    <button
      class="mt-2 px-6 py-3 bg-green-500 hover:bg-green-600 transition rounded-full font-semibold text-white"
    >
      Book a Visit
    </button>
  </div>
</section> 

<section class="py-10 px-6 text-center">
  <h2 class="text-2xl font-bold mb-4">Lighting Experts in Sikar</h2>
  <p>
    City Lights Sikar provides the best lighting services for weddings,
    parties, and events. We offer LED lighting, decorative lights,
    and complete event setup across Sikar Rajasthan.
  </p>
</section>

       <!-- <section class="bg-cover relative h-screen" :style="{ backgroundImage: `url(${bgImage})`}">
          
          <div class="absolute inset-0 bg-black  opacity-25"></div>
          <div class="relative flex items-center justify-center h-full text-center text-white px-4">
             
             <div class="w-full md:w-3/5">

                <h1 class="text-4xl md:text-5xl font-bold mb-4"> Fast & Easy Way To Rent A Car</h1>
                <p class="text-md md:text-xl mb-6">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sit, architecto temporibus! Eius fugiat explicabo cumque numquam obcaecati corrupti ullam quas!</p>

                <h2 class="text-2xl font-semibold">Easy steps for renting a car</h2>

             </div>

          </div>
        
       </section> -->
</template>

<script setup>
// import { ref, onMounted } from "vue"
import bgImage from "../../assets/images/bg_12.png";
 
</script>

<style>

</style>