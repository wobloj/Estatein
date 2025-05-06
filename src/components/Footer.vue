<script setup lang="ts">
import Logo from './Logo.vue';

</script>

<template>
    <footer>
        <div class="flex flex-col">
            <div class="flex flex-row justify-between mx-40 my-24 gap-20">
                <div class="flex flex-col gap-8">
                    <Logo/>
                    <div class="py-5 px-6 flex flex-row gap-2.5 border border-grey-150 rounded-2xl">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6 text-grey-600">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                        </svg>
                        <input type="text" placeholder="Enter Your Email" class="outline-0 bg-grey-80 w-[300px] px-4"/>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="size-6 fill-white cursor-pointer transition-colors hover:fill-purple-500">
                            <path d="M498.1 5.6c10.1 7 15.4 19.1 13.5 31.2l-64 416c-1.5 9.7-7.4 18.2-16 23s-18.9 5.4-28 1.6L284 427.7l-68.5 74.1c-8.9 9.7-22.9 12.9-35.2 8.1S160 493.2 160 480l0-83.6c0-4 1.5-7.8 4.2-10.8L331.8 202.8c5.8-6.3 5.6-16-.4-22s-15.7-6.4-22-.7L106 360.8 17.7 316.6C7.1 311.3 .3 300.7 0 288.9s5.9-22.8 16.1-28.7l448-256c10.7-6.1 23.9-5.5 34 1.4z"/>
                        </svg>
                    </div>
                </div>
                <div>
                    <div class="grid grid-cols-5 gap-5">
                        <div>
                             <h3 class="mb-8 text-xl text-grey-600">Home</h3>
                             <div class="flex flex-col items-start justify-start gap-5 text-[18px]">
                                <a class="transition-colors hover:text-purple-500" href="#">Hero Section</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Features</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Properties</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Testimonials</a>
                                <a class="transition-colors hover:text-purple-500" href="#">FAQ's</a>
                             </div>
                        </div>
                        <div>
                             <h3 class="mb-8 text-xl text-grey-600">About Us</h3>
                             <div class="flex flex-col items-start justify-start gap-5 text-[18px]">
                                <a class="transition-colors hover:text-purple-500" href="#">Our Story</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Our Works</a>
                                <a class="transition-colors hover:text-purple-500" href="#">How It Works</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Our Team</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Our Clients</a>
                             </div>
                        </div>
                        <div>
                             <h3 class="mb-8 text-xl text-grey-600">Properties</h3>
                             <div class="flex flex-col items-start justify-start gap-5 text-[18px]">
                                <a class="transition-colors hover:text-purple-500" href="#">Portfolio</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Featur Categorieses</a>
                             </div>
                        </div>
                        <div>
                             <h3 class="mb-8 text-xl text-grey-600">Services</h3>
                             <div class="flex flex-col items-start justify-start gap-5 text-[18px]">
                                <a class="transition-colors hover:text-purple-500" href="#">Valuation Mastery</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Strategic Marketing</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Negotiation Wizardry</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Closing Success</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Property Management</a>
                             </div>
                        </div>
                        <div>
                             <h3 class="mb-8 text-xl text-grey-600">Contact Us</h3>
                             <div class="flex flex-col items-start justify-start gap-5 text-[18px]">
                                <a class="transition-colors hover:text-purple-500" href="#">Contact Form</a>
                                <a class="transition-colors hover:text-purple-500" href="#">Our Offices</a>
                             </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex flex-row items-center justify-between bg-grey-100 px-40 py-4">
                <div class="flex flex-row gap-9">
                    <p class="font-medium text-[18px]">@2023 Estatein. All Rights Reserved.</p>
                    <a class="font-medium text-[18px] transition-colors hover:text-purple-500" href="#">Terms & Conditions</a>
                </div>
                <div class="flex flex-row gap-2.5">
                    <div class="w-14 aspect-square bg-grey-80 rounded-full flex justify-center items-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" class="size-6 fill-white">
                            <path d="M80 299.3V512H196V299.3h86.5l18-97.8H196V166.9c0-51.7 20.3-71.5 72.7-71.5c16.3 0 29.4 .4 37 1.2V7.9C291.4 4 256.4 0 236.2 0C129.3 0 80 50.5 80 159.4v42.1H14v97.8H80z"/>
                        </svg>
                    </div>
                    <div class="w-14 aspect-square bg-grey-80 rounded-full flex justify-center items-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="size-6 fill-white">
                            <path d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"/>
                        </svg>
                    </div>
                    <div class="w-14 aspect-square bg-grey-80 rounded-full flex justify-center items-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="size-6 fill-white">
                            <path d="M459.4 151.7c.3 4.5 .3 9.1 .3 13.6 0 138.7-105.6 298.6-298.6 298.6-59.5 0-114.7-17.2-161.1-47.1 8.4 1 16.6 1.3 25.3 1.3 49.1 0 94.2-16.6 130.3-44.8-46.1-1-84.8-31.2-98.1-72.8 6.5 1 13 1.6 19.8 1.6 9.4 0 18.8-1.3 27.6-3.6-48.1-9.7-84.1-52-84.1-103v-1.3c14 7.8 30.2 12.7 47.4 13.3-28.3-18.8-46.8-51-46.8-87.4 0-19.5 5.2-37.4 14.3-53 51.7 63.7 129.3 105.3 216.4 109.8-1.6-7.8-2.6-15.9-2.6-24 0-57.8 46.8-104.9 104.9-104.9 30.2 0 57.5 12.7 76.7 33.1 23.7-4.5 46.5-13.3 66.6-25.3-7.8 24.4-24.4 44.8-46.1 57.8 21.1-2.3 41.6-8.1 60.4-16.2-14.3 20.8-32.2 39.3-52.6 54.3z"/>
                        </svg>
                    </div>
                    <div class="w-14 aspect-square bg-grey-80 rounded-full flex justify-center items-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" class="size-6 fill-white">
                            <path d="M549.7 124.1c-6.3-23.7-24.8-42.3-48.3-48.6C458.8 64 288 64 288 64S117.2 64 74.6 75.5c-23.5 6.3-42 24.9-48.3 48.6-11.4 42.9-11.4 132.3-11.4 132.3s0 89.4 11.4 132.3c6.3 23.7 24.8 41.5 48.3 47.8C117.2 448 288 448 288 448s170.8 0 213.4-11.5c23.5-6.3 42-24.2 48.3-47.8 11.4-42.9 11.4-132.3 11.4-132.3s0-89.4-11.4-132.3zm-317.5 213.5V175.2l142.7 81.2-142.7 81.2z"/>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>