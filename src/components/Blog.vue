<script setup>
import Contact from '@/components/Contact.vue';
</script>

<template>
  <!--Stories Section-->
  <section class="stories-section overflow-hidden">
      <div class="container mx-auto text-yellow md:px-12">
         <!--Flex Container-->
        <div class="flex flex-col pt-30 items-center justify-between md:flex-row ">
          <div class="py-6 md::pt-0 ">
            <h2 class="text-3xl md:text-6xl">
              "stories ,"
              <br /><span>historias,</span> <br /><span>ictopii,</span> <br /><span>iotopice</span>
            </h2>
          </div>
          <div class="flex flex-col justify-end">
            <p class="text-lg text-right md:text-2xl">
              Aug 08 2025
              <br />
              Angkor Wat,Cambodia.
            </p>
          </div>
        </div>
        <!--grid box-->
        <div class="grid pt-20 md:pt-40 px-6 md:grid-cols-2 md:px-0 md:pb-6">
          <div class="">
            <h2 class=" text-xl md:text-4xl">Let,s hear them.</h2>
          </div>
          <div class="flex justify-end">
            <p class=" text-lg md:text-2xl font-light">#stories</p>
          </div>
        </div>
      </div>
    </section>
     <contact/>
</template>

<style>

</style>