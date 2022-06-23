<script setup>
// import statements here
//bg-[url('./assets/MaskGroup.svg')]

</script>

<template>
<!--adding two horizontal cards-->
 <div class="grid grid-cols-1 md:grid-cols-2">
  <!--Text & Buttons-->
  <div class="w-[100%] p-6 space-y-5 break-words">
    <div>
      <h1 class="text-[45px] text-left"><span class="text-pink-600">Pacific</span> <span class="text-blue-900">Centralized Data Storage in RAW</span></h1>
    </div>
    <div class="text-[16px] text-left space-y-3">
      <p>Store data in RAW and unstructured data then select and organize the data when needed from the centralized DataLake.</p>
      <p>
        Our AI Engine will help you visualize the data in real-time when you make a search query.
      </p>
      </div>
      
      <!--buttons-->
      <div class="text-left">
        <button class="bg-pink-600 hover:scale-110 text-white text-xs mt-20 ml-2 mr-2 py-2 px-4 rounded-full inset-0" href="#pablo">
              WHY PACIFIC
      </button>
      <button class="bg-transparent text-black text-xs mt-20 py-2 px-6 border border-blue-500 hover:scale-110 rounded-full" href="#pablo">
              Learn More
      </button>
    </div>
    </div>
  
  <!--Overlapping images-->
  <div class=" w-[100%] h-[500px] md:h-[750px] p-6 space-y-5">
    <!--SVG starts here-->
  <div class="flex items-center justify-center ">
    <img src="../assets/Macbook.png" class=" opacity-90 h-[500px] md:h-auto">
 </div>
  </div>
 </div>
</template>

<style scoped>
/*a {
  color: #42b983;
}*/
</style>
