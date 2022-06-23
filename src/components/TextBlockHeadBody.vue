<script setup>
// import statements here
import { ref } from 'vue';
const props=defineProps({
    headingText:String,
    paragraphText:String,
})
</script>

<template>
<!--adding two horizontal cards-->
<div class="flex flex-col">
    <div class="basis-2/3 mx-auto text-3xl text-blue-900 font-bold">
        <h1 >
            {{headingText}}
        </h1>
    </div>
    <div class="basis-1/3 text-sm mx-auto text-gray-900 md:w-[60%]">
            {{paragraphText}}
    </div>
</div>
  
</template>

<style scoped>
/*a {
  color: #42b983;
}*/
</style>
