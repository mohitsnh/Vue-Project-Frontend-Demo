<template >
    <button class=" h-9  shadow-ll w-[120px] text-xs duration-200 rounded hover:scale-110" :class="color ,rounded ,margin" >{{dataValue}}</button>
</template>

<script setup lang="ts">
import { ref } from 'vue';
const props=defineProps({
    color:String,
    rounded:String,
    margin:String,
    dataValue:String,
})
</script>