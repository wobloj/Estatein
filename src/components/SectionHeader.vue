<script setup>
    import ButtonPrimary from './ButtonPrimary.vue';
import StarDecoration from './StarDecoration.vue';

    defineProps({
        header:{
            type:String,
        },
        paragraph:{
            type:String,
        },
        buttonText:{
            type:String,
            default:'Button'
        },
        buttonVisible:{
            type:Boolean,
            default:true
        }
    })
</script>

<template>
    <div>
        <StarDecoration/>
        <div class="flex flex-row items-end justify-between gap-48">
            <div>
                <h1 class="font-semibold text-5xl mb-10">{{header}}</h1>
                <p class="text-grey-600 text-base">{{paragraph}}</p>
            </div>
            <ButtonPrimary v-if="buttonVisible" :color="'bg-grey-100'">{{ buttonText }}</ButtonPrimary>
        </div>
    </div>
</template>