<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div
    class="flex flex-col bg-no-repeat bg-cover w-full font-bold stars bg-[#FFF6ED] text-[#194027] text-base min-h-full font-space"
  >
  <div class="flex flex-col md:flex-row justify-around items-center content-center"> 
    <div class="my-name flex uppercase text-8xl">
      Dahlia <br> Salem
    </div> 
    <div class="my-image flex">
      <img src="@/assets/pic.jpg" 
      class="mx-auto sm:max-w-md lg:max-w-xl h-80">
    </div> 
  </div>
  </div>
</template>

<style scoped>
</style>
