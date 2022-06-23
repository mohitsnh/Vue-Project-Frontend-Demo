<script setup>
// import statements here

</script>

<template>
<!--adding two horizontal cards-->
<section class="mt-4">
    <!--sign-up-block-->
    <div class="bg-blue-900 flex flex-col md:flex-row text-white h-[120px] md:h-[80px] items-center">
      
        <!--col 1 text-->
        <div class="text-3xl md:w-[50%] h-[50%] md:h-auto mt-2 md:mt-0">
            <h1>Sign Up To Get Latest Updates</h1>
        </div>
        <!--col 2 Buttons   -->
        <div class="md:w-[50%] h-[50%] md:h-auto md:px-5">
            <input
              type="text" class="w-[300px] p-2 text-sm border border-grey-light text-grey-dark"/>
            <button class="w-[100px] p-3 text-xs text-white bg-pink-500">
              Sign up
            </button>
        </div>
      
    </div>
</section>
</template>

<style scoped>
/*a {
  color: #42b983;
}*/
</style>
