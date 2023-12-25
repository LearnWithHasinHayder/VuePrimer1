<script setup>
import Tagline from './components/Tagline.vue';
import Hero from './components/Hero.vue';
import VideoButton from './components/VideoButton.vue';
import LogoSection from './components/LogoSection.vue';
import svgIcon from './assets/vue.svg'
</script>

<template>
  <section class="bg-white ">
    <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12">
      <Tagline/>
      <Hero/>
      <div class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
        <VideoButton/>
        <video-button/>
      </div>
      <LogoSection/>
    </div>
  </section>
</template>

<style scoped>

</style>
