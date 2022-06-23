<script setup lang="ts">
import { ref } from 'vue'
import ButtonContainer from './ButtonContainer.vue'
defineProps({
  msg: String
})
const count = ref(0);
const hiddenStatus = ref(true);
const buttonName = 'Request for DEMO'
console.log(buttonName);
</script>

<template>
 <nav class=" flex z-40 sticky items-center justify-between px-2 py-3 mb-3 top:0">
  <div class="container px-4 mx-auto flex md:flex-nowrap md:flex-items-center justify-between">
    <div class="w-full relative flex justify-between lg:w-auto  px-4 lg:static lg:block lg:justify-start">
      <a class="text-sm leading-relaxed inline-block mr-4 py-2 whitespace-nowrap" href="#pablo">
        <div class="logo-image">
            <img src="../assets/Frame 2.png" class= "h-5 w-[100px] m-2 object-fill relative">
      </div>
      </a>
      <button class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none" type="button">
        <span class="block relative w-6 h-px rounded-sm bg-white"></span>
        <span class="block relative w-6 h-px rounded-sm bg-white mt-1"></span>
        <span class="block relative w-6 h-px rounded-sm bg-white mt-1"></span>
      </button>
    </div>
    <div class="lg:flex flex-grow md:flex-wrap items-center" id="example-navbar-warning">
      <ul class="flex md:flex-row lg:flex-row flex-shrink list-none ml-auto">
          <li class="nav-item hidden md:flex">
            <a class="px-3 py-2 flex items-center not-italic font-normal text-sm leading-6 text-blue-900 hover:opacity-75" href="#pablo">
              Features
            </a>
          </li>
          <li class="nav-item hidden md:flex">
            <a class="px-3 py-2 flex items-center not-italic font-normal text-sm leading-6 text-blue-900 hover:opacity-75" href="#pablo">
              About
            </a>
          </li>
          <li class="nav-item hidden md:flex">
            <a class="px-3 py-2 flex items-center not-italic font-normal text-sm leading-6 text-blue-900 hover:opacity-75" href="#pablo">
              Contact
            </a>
          </li>
          <li class="nav-item">
           <!--- <button class="bg-pink-600 hover:bg-pink-800 text-white flex-shrink font-bold ml-2 mr-2 py-2 px-4 rounded-full" href="#pablo">
              Request For Demo
            </button>-->
            <ButtonContainer rounded="rounded-[50px]" color="bg-pink-600 text-white" :dataValue=buttonName></ButtonContainer>
          </li>
          <li class="nav-item hidden md:flex">
          <div class="logo-image">
            <img src="../assets/Vector.png" class= "h-6 m-2 object-cover relative hover:scale-105" href="#pablo">
          </div>
          </li>
          <li class="nav-item md:hidden flex">
          <button class="px-3 py-2" @click="hiddenStatus = !hiddenStatus">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          </button>
          </li>

      </ul>
    </div>
  </div>
</nav>
<div class="md:hidden text-right" :class="{hidden: hiddenStatus}">
  <a href="/" class="block py-1 px-4">Features</a>
  <a href="/" class="block py-1 px-4">About</a>
  <a href="/" class="block py-1 px-4">Content</a>
</div>
</template>

<style scoped>
/*a {
  color: #42b983;
}*/
</style>
