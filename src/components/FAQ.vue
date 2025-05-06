<script setup lang="ts">
import ButtonPrimary from './ButtonPrimary.vue';
import Navigation from './Navigation.vue';
import SectionHeader from './SectionHeader.vue';

</script>

<template>
    <section class="mx-20 my-40">
        <SectionHeader 
        header="Frequently Asked Questions" 
        paragraph="Find answers to common questions about Estatein's services, property listings, and the real estate process. We're here to provide clarity and assist you every step of the way." 
        buttonText="View All FAQ's"/>

        <div class="grid grid-cols-3 gap-8 mt-20">
            <div class="flex flex-col items-start gap-8 border border-grey-150 rounded-lg p-[50px]">
                <h2 class="font-semibold text-2xl">How do I search for properties on Estatein?</h2>
                <p class="font-medium text-[18px] text-grey-600">Learn how to use our user-friendly search tools to find properties that match your criteria.</p>
                <ButtonPrimary>Read More</ButtonPrimary>
            </div>
            <div class="flex flex-col items-start gap-8 border border-grey-150 rounded-lg p-[50px]">
                <h2 class="font-semibold text-2xl">What documents do I need to sell my property through Estatein?</h2>
                <p class="font-medium text-[18px] text-grey-600">Find out about the necessary documentation for listing your property with us.</p>
                <ButtonPrimary>Read More</ButtonPrimary>
            </div>
            <div class="flex flex-col items-start gap-8 border border-grey-150 rounded-lg p-[50px]">
                <h2 class="font-semibold text-2xl">How can I contact an Estatein agent?</h2>
                <p class="font-medium text-[18px] text-grey-600">Discover the different ways you can get in touch with our experienced agents.</p>
                <ButtonPrimary>Read More</ButtonPrimary>
            </div>
        </div>
        <Navigation numberOfPages="10"/>
    </section>
</template>