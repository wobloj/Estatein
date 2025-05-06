<script setup>
    defineProps({
        numberOfPages:{
            type: String,
            default: 1
        }
    })
</script>

<template>
    <hr class="border-t border-grey-150 mt-20 mb-5"/>
    <div class="flex flex-row justify-between items-start">
            <p class="font-medium text-[20px] text-grey-600"><span class="text-white">01</span> of {{ numberOfPages }}</p>
            <div class="flex flex-row gap-2.5">
                <button class="rounded-full flex items-center justify-center w-14 aspect-square border transition-colors hover:border-grey-300 border-grey-150 bg-grey-80 cursor-pointer">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6 fill-grey-500">
                        <path fill-rule="evenodd" d="M11.03 3.97a.75.75 0 0 1 0 1.06l-6.22 6.22H21a.75.75 0 0 1 0 1.5H4.81l6.22 6.22a.75.75 0 1 1-1.06 1.06l-7.5-7.5a.75.75 0 0 1 0-1.06l7.5-7.5a.75.75 0 0 1 1.06 0Z" clip-rule="evenodd" />
                    </svg>
                </button>
                <button class="rounded-full flex items-center justify-center w-14 aspect-square border transition-colors hover:border-grey-300 border-grey-150 bg-grey-100 cursor-pointer">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path fill-rule="evenodd" d="M12.97 3.97a.75.75 0 0 1 1.06 0l7.5 7.5a.75.75 0 0 1 0 1.06l-7.5 7.5a.75.75 0 1 1-1.06-1.06l6.22-6.22H3a.75.75 0 0 1 0-1.5h16.19l-6.22-6.22a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
        </div>
</template>