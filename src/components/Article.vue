<script setup lang="ts">
import TextBlockHeadBody from './TextBlockHeadBody.vue'
const headingSectionC = "Latest Articles";
const textSectionC = "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus";
</script>

<template>
<div class="bg-blue-50 my-16">
    <div class="p-2 mx-[10%]">
    <TextBlockHeadBody :headingText=headingSectionC :paragraphText=textSectionC></TextBlockHeadBody>
    </div>
    <div class="grid md:grid-cols-3 gap-2 w-auto mx-[10%] p-2 h-auto place-items-center">
    <!--Card 1-->
        <div class=" bg-white rounded-lg border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700 my-10">
            <div class="w-[1/3]">
                <a href="#" class="">
                <img class="rounded-t-lg w-full" src="../assets/Card-Image-1.png" alt="" />
                </a>
            
                <div class="p-5 text-left">
                <a href="#">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                </a>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Artificial intelligence powers many of the technologies and services underpinning Uber’s platform, allowing engineering and data science teams to make informed decisions that help improve user experiences for products across our lines of business.</p>
                <a href="#" class="inline-flex items-center py-2 px-3 text-sm font-bold text-center text-pink-600 bg-none rounded-lg hover:scale-110 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    Read more
                </a>
                </div>
            </div>
        </div>
    <!--Card 2-->
        <div class=" bg-white rounded-lg border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700 my-10">
            <div class="w-[1/3]">
                <a href="#">
                    <img class="rounded-t-lg w-full" src="../assets/Card-Image-2.png" alt="" />
                </a>
                <div class="p-5 text-left">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                    </a>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Artificial intelligence powers many of the technologies and services underpinning Uber’s platform, allowing engineering and data science teams to make informed decisions that help improve user experiences for products across our lines of business.</p>
                    <a href="#" class="inline-flex items-center py-2 px-3 text-sm font-bold text-center text-pink-600 bg-none rounded-lg hover:scale-110 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                        Read more
                    </a>
                </div>
            </div>
        </div>
    <!--Card 3-->
        <div class=" bg-white rounded-lg border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700 my-10">
            <div class="w-[1/3]">
                <a href="#" class="">
                    <img class="rounded-t-lg items-center w-full" src="../assets/Card-Image-3.png" alt="" />
                </a>
                <div class="p-5 text-left">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                    </a>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Artificial intelligence powers many of the technologies and services underpinning Uber’s platform, allowing engineering and data science teams to make informed decisions that help improve user experiences for products across our lines of business.</p>
                    <a href="#" class="inline-flex items-center py-2 px-3 text-sm font-bold text-center text-pink-600 bg-none rounded-lg hover:scale-110 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                        Read more
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>

</template>

<style>

</style>