<script setup>
import About from '@/components/About.vue';
import Blog from '@/components/Blog.vue';
import Contact from '@/components/Contact.vue';
</script>
<!--Hero Section-->
<template>
  <section id="hero" class="bg-white hero">
        <!--Flex Container-->
        <div class="container mx-auto flex flex-col justify-between gap-6 md:flex-row mt-10 p-8">
          <!--item left-->
          <div class=" flex justify-center md:justify-start items-center md:w-1/2 md:p-y-0">
          <img class="" src="../assets/image/hero-img.webp"/>
        </div>
        <!--item-right-->
        <div class="flex flex-col font-light justify-center items-center md:items-start md:w-1/2">
          <h2 class="text-3xl capitalize ">headline</h2>
          <p class="text-lg p-6 md:p-0">
            Storytelling, expert analysis, and vivid descriptions. The Stories Podcast brings
            history to life, making it accessible and engaging for a global audience
          </p>
        </div>
        </div>
  </section>
  <About/>
</template>
