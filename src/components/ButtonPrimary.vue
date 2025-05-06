<script setup>
    defineProps({
        color:{
            type: String,
            default: 'bg-grey-80'
        }
    })
</script>

<template>
    <button :class="[color]" class="rounded-lg text-lg border whitespace-nowrap transition-colors hover:border-grey-300 border-grey-150  cursor-pointer py-3 px-6">
        <slot></slot>
    </button>
</template>