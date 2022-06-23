<script setup lng="ts">
defineProps({
  imgPropUrl: String,
})
</script>
<template>
    <div class=" bg-white rounded-lg border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700 w-[450px] h-[200px]">
            <div class="w-[1/3]">
                <a href="#" class="">
                <img class="rounded-t-lg w-full" :src="imgPropUrl" alt="" />
                </a>
            
                <div class="p-5 text-left">
                <a href="#">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                </a>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Artificial intelligence powers many of the technologies and services underpinning Uber’s platform, allowing engineering and data science teams to make informed decisions that help improve user experiences for products across our lines of business.</p>
                <a href="#" class="inline-flex py-2 px-3 text-sm font-bold text-center text-pink-600 bg-none rounded-lg hover:scale-110 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    Read more
                </a>
                </div>
            </div>
        </div>
</template>

<style>
</style>