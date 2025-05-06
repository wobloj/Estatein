<script setup >
    import Banner from './Banner.vue';
    import ButtonPrimary from './ButtonPrimary.vue';
import Logo from './Logo.vue';
</script>
<template>
    <Banner/>
    <header class="flex flex-row justify-around items-center h-24 bg-grey-100 text-white">
        <Logo/>
        <nav>
            <ul class="flex flex-row items-center gap-[30px] text-lg">
                <li><a href="#" class="rounded-lg border border-grey-150 bg-grey-80 px-6 py-3">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Properties</a></li>
                <li><a href="#">Services</a></li>
            </ul>
        </nav>
        <div>
            <ButtonPrimary>Contact Us</ButtonPrimary>
        </div>
    </header>
</template>