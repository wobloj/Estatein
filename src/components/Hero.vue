<script setup>
    import ButtonPrimary from './ButtonPrimary.vue';
import ButtonSecondary from './ButtonSecondary.vue';
</script>

<template>
    <main class="flex flex-col">
        <div class="flex flex-row justify-around items-start relative">
            <div class="flex flex-col mb-40 gap-14 w-[920px] bg-grey-80 text-white ml-40 mr-10">
                <div class="">
                    <h1 class="text-6xl font-semibold mt-40 mb-6 w-9/12">Discover Your Dream Property with Estatein</h1>
                    <p class="text-grey-600 w-10/12">Your journey to finding the perfect property begins here. Explore our listings to find the home that matches your dreams.</p>
                </div>
                <div class="flex flex-row gap-4">
                    <ButtonPrimary> Learn More</ButtonPrimary>
                    <ButtonSecondary>Browse Properties</ButtonSecondary>
                </div>
                <div class="flex flex-row gap-8">
                    <div class="py-4 px-6 bg-grey-100 border border-grey-150 rounded-lg w-50">
                        <h2 class="text-4xl font-bold mb-1">200+</h2>
                        <p class="text-sm text-grey-600">Happy Customers</p>
                    </div>
                    <div class="py-4 px-6 bg-grey-100 border border-grey-150 rounded-lg w-50">
                        <h2 class="text-4xl font-bold mb-1">10k+</h2>
                        <p class="text-sm text-grey-600">Properties For Clients</p>
                    </div>
                    <div class="py-4 px-6 bg-grey-100 border border-grey-150 rounded-lg w-50">
                        <h2 class="text-4xl font-bold mb-1">16+</h2>
                        <p class="text-sm text-grey-600">Years of Experience</p>
                    </div>
                </div>
            </div>
            <div class="w-[920px] bg-grey-100">
                <img src="../assets/building.png" alt="Building image" class=""/>
            </div>

            <div class="rounded-full absolute w-40 aspect-square border border-grey-150 bg-grey-80 translate-x-[100px] translate-y-[120px]">
                <svg viewBox="0 0 300 300" class="absolute p-3 w-full h-full">
                    <defs>
                    <path
                        id="textCircle"
                        d="M150,150 m-120,0 a120,120 0 1,1 240,0 a120,120 0 1,1 -240,0"
                    />
                    </defs>
                    <text
                    fill="white"
                    font-size="30"
                    font-weight="bold"
                    font-family="sans-serif"
                    textLength="700"
                    >
                    <textPath href="#textCircle" startOffset="0">
                        Discover Your Dream Property ✨
                    </textPath>
                </text>
                </svg>
                <div class="flex flex-col items-center justify-center rounded-full absolute w-20 aspect-square border border-grey-150 bg-grey-100 translate-x-[40px] translate-y-[37px]">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-10">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                    </svg>
                </div>
            </div>
        </div>
        <div class="flex flex-row gap-5 justify-center items-center bg-grey-80 py-5 outline-8 outline-grey-100 font-semibold">
            <div class="w-[450px] h-52 flex flex-col items-center justify-center gap-5 bg-grey-100 rounded-xl border border-grey-150 relative">
                <img src="../assets/hero/heroicon1.png"/>
                <p>Find Your Dream Home </p>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 absolute top-0 right-0 m-5 opacity-20 transition-opacity hover:opacity-100">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
            </div>
            <div class="w-[450px] h-52 flex flex-col items-center justify-center gap-5 bg-grey-100 rounded-xl border border-grey-150 relative">
                <img src="../assets/hero/heroicon2.png"/>
                <p>Unlock Property Value</p>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 absolute top-0 right-0 m-5 opacity-20 transition-opacity hover:opacity-100">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
            </div>
            <div class="w-[450px] h-52 flex flex-col items-center justify-center gap-5 bg-grey-100 rounded-xl border border-grey-150 relative">
                <img src="../assets/hero/heroicon3.png"/>
                <p>Effortless Property Management</p>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 absolute top-0 right-0 m-5 opacity-20 transition-opacity hover:opacity-100">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
            </div>
            <div class="w-[450px] h-52 flex flex-col items-center justify-center gap-5 bg-grey-100 rounded-xl border border-grey-150 relative">
                <img src="../assets/heroicon4.png"/>
                <p>Smart Investments, Informed Decisions</p>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 absolute top-0 right-0 m-5 opacity-20 transition-opacity hover:opacity-100">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
            </div>
        </div>
    </main>
</template>