<script>
export default {
  emits: ["mouseenter", "mouseout"],
  props: ["slide", "currentSlide", "index", "direction"],
  computed: {
    transitionEffect() {
      return this.direction === "right" ? "slide-out" : "slide-in";
    },
  },
};
</script>

<template>
  <transition :name="transitionEffect">
    <div
      class="carousel-item"
      v-show="currentSlide === index"
      @mouseenter="$emit('mouseenter')"
      @mouseout="$emit('mouseout')"
    >
      <!-- <img :src="slide"/> -->
      <!-- <CarouselCard :imageProp="slide"></CarouselCard>  -->
      <!---The card componenet starts here-->
      <div class=" bg-white rounded-lg border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700 w-[300px] h-[400px]">
            <div class="w-[1/3]">
                <a href="#" class="">
                <img class="rounded-t-lg w-auto" :src="slide" alt=""/>
                </a>
                <div class="p-5 text-left">
                <a href="#">
                    <h5 class="mb-2 font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
                </a>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Artificial intelligence powers many of the technologies and services underpinning Uber’s platform, allowing engineering and data science teams to make informed decisions that help improve user experiences for products across our lines of business.</p>
                <a href="#" class="inline-flex py-2 px-3 text-sm font-bold text-center text-pink-600 bg-none rounded-lg hover:scale-110 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    Read more
                </a>
             </div>
          </div>
      </div>
      <!---The card componenet ends here-->
  </div>
  </transition>
</template>


<style scoped>
.carousel-item {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
.slide-in-enter-active,
.slide-in-leave-active,
.slide-out-enter-active,
.slide-out-leave-active {
  transition: all 1s ease-in-out;
}
.slide-in-enter-from {
  transform: translateX(-100%);
}
.slide-in-leave-to {
  transform: translateX(100%);
}
.slide-out-enter-from {
  transform: translateX(100%);
}
.slide-out-leave-to {
  transform: translateX(-100%);
}
</style>