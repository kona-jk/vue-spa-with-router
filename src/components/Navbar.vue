<script setup>
  import {ref} from "vue";
  const navOpen = ref(false);

</script>
<template>
  <header class="">
    <!--Navbar-->
<nav class="bg-white fixed w-full z-20 top-0 start-0 min-h-20 flex items-center">
  <!--Flex Container-->
  <div class=" container flex flex-col justify-center items-center space-y-2 md:space-y-0 md:flex-row md:justify-between mx-auto p-8">
    <!--Logo-->
    <RouterLink to = "/"
           class="flex items-center space-x-3 rtl:space-x-reverse" aria-current="logo"><span class="self-center text-4xl text-heading font-light whitespace-nowrap text-gray-900">KONA.jk</span>
          </RouterLink>
          <!--Mobile Menu-->
          <div class="flex flex-col items-center">
<button @click="navOpen=!navOpen" type="button" class="inline-flex items-center p-2 w-12 h-12 justify-center text-sm text-body rounded-base md:hidden hover:bg-indigo-500 hover:text-heading focus:outline-none focus:ring-2 focus:ring-neutral-tertiary" aria-controls="navbar-default" aria-expanded="false">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" :class="navOpen ? 'hidden' : '' ">
       <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12" />
       </svg>
        <svg class="" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" :class="navOpen ? '' : 'hidden'">
       <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5M12 17.25h8.25" />
       </svg>
    </button>
    <div :class="navOpen ? 'hidden' : '' "  class="w-full md:block md:w-auto" id="navbar">
      <ul class="text-lg  flex flex-col p-4 md:flex-row md:p-0 md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-neutral-primary">
        <li>
          <RouterLink to = '/about'
           class="block py-2 px-3 text-black bg-brand rounded md:bg-transparent md:text-fg-brand md:p-0" aria-current="page">About
          </RouterLink>
        </li>
        <li>
          <RouterLink to = '/blog'
           class="block py-2 px-3 text-black bg-brand rounded md:bg-transparent md:text-fg-brand md:p-0" aria-current="page">Blog
          </RouterLink>
        </li>
        <li>
          <RouterLink to = '/contact'
           class="block py-2  px-3 text-black bg-brand rounded md:bg-transparent md:text-fg-brand md:p-0" aria-current="page">Contact
          </RouterLink>
        </li>
      </ul>
    </div>
          </div>
    
  </div>
</nav>
  </header>
</template>



<style scoped>

 
</style>
