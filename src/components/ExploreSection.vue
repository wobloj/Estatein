<script setup lang="ts">
import ButtonSecondary from './ButtonSecondary.vue';

</script>

<template>
    <section class="relative border border-grey-150">
        <img src="../assets/abstractexploreleft.png" alt="" class="absolute -z-10 h-full left-0 top-0">
        <div class="flex flex-row items-center gap-64 my-24 mx-40">
            <div>
                <h1 class="text-5xl font-semibold mb-3.5">Start Your Real Estate Journey Today</h1>
                <p class="font-normal text-[18px] text-grey-600">Your dream property is just a click away. Whether you're looking for a new home, a strategic investment, or expert real estate advice, Estatein is here to assist you every step of the way. Take the first step towards your real estate goals and explore our available properties or get in touch with our team for personalized assistance.</p>
            </div>
            <ButtonSecondary>
                Explore Properties
            </ButtonSecondary>
        </div>
        <img src="../assets/abstractexploreright.png" alt="" class="absolute -z-10 h-full right-0 top-0">
    </section>
</template>