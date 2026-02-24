<script setup>
import Blog from '@/components/Blog.vue';
</script>

<template>
    <!--About Section-->  
  <section class="bg-black w-full bg-cover relative">
     <!--Flex Container-->
      <div class=" container mx-auto h-screen flex flex-col-reverse justify-between items-center md:flex-row md:space-x-6 ">
          <!--Left item-->
          <div class="text-white text-center flex flex-col flex-wrap md:p-8 md:text-left md:w-1/2">
            <h2 class="text-xl capitalize md:text-2xl">About the event</h2>
            <p class="font-light p-6 md:px-0 md:text-l">
              Held over a weekend, the event is structured around a series of exhibitions,
              workshops, and panel discussions. The exhibitions showcase a curated selection of
              photographs that tell compelling stories from various corners of the globe, each image
            </p>
          </div>
              <!--Right item-->
          <div class="overflow-hidden mb-10 md:w-1/2 md:mr-8 ">
        <img class="bg-cover" src="/src/assets/image/about-img.webp" alt="about-image">
      </div>  
      </div>  
 </section>
    <!--About Info Section-->
    <section class=" flex flex-col-reverse items-center md:flex-row">
      <div class="bg-purple overflow-hidden">
         <!--Flex Container-->
        <div class="container mx-auto md:my-0 lg:my-20  xl:my-50 py-12 px-6 md:p-8">
          <!--Text Info-->
          <div class="text-white text-center flex flex-col justify-center items-center space-y-6 md:text-left">
            <div class="">
              <h2 class="text-xl pb-4 lg:text-2xl">Lewis Hine</h2>
              <p class="text-l md:text-lg mb-6">
                Lewis W. Hine studied sociology before moving to New York in 1901 to work at the
                Ethical Culture School, where he took up photography to enhance his teaching
                practices
              </p>
              <span class="text-l p-1 text-blue-500 md:text-xl"><a href=""> instagram</a></span>
              <span class="text-l p-1 text-blue-500 md:text-xl"><a href=""> tiktok</a></span>
            </div>
            <div class="">
              <h2 class="text-xl pb-4 lg:text-2xl">Lewis Hine</h2>
              <p class="text-l md:text-lg mb-6">
                Lewis W. Hine studied sociology before moving to New York in 1901 to work at the
                Ethical Culture School, where he took up photography to enhance his teaching
                practices
              </p>
              <span class="text-l p-1 text-blue-500 md:text-xl"><a href=""> instagram</a></span>
              <span class="text-l p-1 text-blue-500 md:text-xl"><a href=""> tiktok</a></span>
            </div>
          </div>
        </div>
      </div>
      <!--About Info Img-->
      <div class="bg-img-4"></div>
    </section>
     <Blog/>
</template>

<style>
</style>