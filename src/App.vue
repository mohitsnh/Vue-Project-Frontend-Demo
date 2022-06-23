<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import NavBar from './components/NavBar.vue'
import CardWithPhoto from './components/CardWithPhoto.vue'
import TextBlockHeadBody from './components/TextBlockHeadBody.vue'
import GridOfCards from './components/GridOfCards.vue'
import SignupSection from './components/SignupSection.vue'
import DataArchitecture  from './components/DataArchitecture.vue'
import Article  from './components/Article.vue'
import Footer from './components/Footer.vue'
import Carousel from "./components/carousel/Carousel.vue";
//import CarouselCard from './components/carousel/CarouselCard.vue'
 //import imgSlide1 from './assets/logo.png'
// import imgSlide2 from './assets/Macbook.png'
 //import imgSlide3 from './assets/logo.png'
//carousel

  let name: "App";
  let components: { Carousel: any };

    
defineProps({
  msg: String,
})

const headingSectionA = "DataLake Features";
const textSectionA = "We provide or ala-carte engineering solutions to your data needs";
const headingSectionB = "DataLake Architecture";
const textSectionB = "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculusy";
const headingSectionC = "DataLake Architecture";
const textSectionC = "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculusy";
  const slides = [
      "../assets/logo.png",
      "https://picsum.photos/id/1035/900/400",
      "https://picsum.photos/id/1036/900/400",];
</script>

<template>

<div class="md:bg-[url('./assets/MaskGroup.svg')] md:bg-no-repeat md:bg-right-top">
  <div class="md:mx-[10%]">
    <NavBar/>
  </div>
  <div class="mx-[10%]">
  <CardWithPhoto/>
  </div>

  <div class="flex justify-center mt-[-80px] mx-[10%]">
  <TextBlockHeadBody :headingText=headingSectionA :paragraphText=textSectionA></TextBlockHeadBody>
  </div>
  <div class="mt-5 mx-[10%]">
    <GridOfCards/>
  </div>
  <div class="flex justify-center mt-4 p-10 mx-[10%]">
  <TextBlockHeadBody :headingText=headingSectionB :paragraphText=textSectionB ></TextBlockHeadBody>
  </div>
  <div class="mx-[10%]"><DataArchitecture/></div>
  <div><Article /></div>
  <div class="flex justify-center mt-4 p-10 mx-[10%]">
  <TextBlockHeadBody :headingText=headingSectionC :paragraphText=textSectionC ></TextBlockHeadBody>
  </div>
  <carousel :slides="slides" :interval="3000" controls indicators></carousel>
  <div><SignupSection/></div>
<Footer />

</div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>