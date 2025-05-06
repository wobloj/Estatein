<script setup>
    import {ref} from 'vue';
    import abstractImage from '../assets/abstract.png';

    const isVisible = ref(true);

    const closeBanner = () => {
        isVisible.value = false;
        console.log('Banner closed');
    };

</script>

<template>
    <div :style="{ backgroundImage: `url(${abstractImage})`}" class=" flex flex-row justify-between items-center h-14 bg-grey-150 text-white" :class=" [isVisible ? 'block' : 'hidden']">
        <div></div>
        <div class="ml-28">✨Discover Your Dream Property with Estatein <a href="#" class="ml-2 underline transition-colors hover:text-purple-500">Learn More</a></div>
        <div @click="closeBanner()" class=" rounded-full mr-5 bg-white/10 px-[11px] py-1 cursor-pointer">X </div>
    </div>
</template>