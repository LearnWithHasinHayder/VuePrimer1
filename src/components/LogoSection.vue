<script setup>
    import Logo1 from './Logo1.vue';
    import Logo2 from './Logo2.vue';
    import Logo3 from './Logo3.vue';
</script>
 
<template>
    <div class="px-4 mx-auto text-center md:max-w-screen-md lg:max-w-screen-lg lg:px-36">
        <span class="font-semibold text-gray-400 uppercase">FEATURED IN</span>
        <div class="flex flex-wrap justify-center items-center mt-8 text-gray-500 sm:justify-between">
            <Logo1/>
            <Logo2/>
            <Logo3/>
        </div>
    </div>
</template>
 
<style scoped></style>