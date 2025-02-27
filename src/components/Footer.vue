<script setup>

const year = new Date().getFullYear();
</script>
<template>
    <div class="border-t-3 border-black">
        <div class="flex flex-col md:flex-row justify-center md:justify-between pt-4 md:pt-10 container mx-auto px-4 py-6">
            <div class="flex items-center gap-2 md:gap-4 mb-6 md:mb-0">
                <img class="w-8 md:w-auto" src="/images/Vector.svg" alt="logo">
                <p class="text-xl md:text-2xl font-bold font-handlee">znisa</p>
            </div>
            <div class="text-center">
                <div class="flex flex-col md:flex-row gap-2 md:gap-4 justify-center">
                    <a href="" class="text-lg md:text-2xl font-handlee bg-black text-white px-4 py-2">Twitter X</a>
                    <a href="" class="text-lg md:text-2xl font-handlee bg-black text-white px-4 py-2">Linkedin</a>
                    <a href="" class="text-lg md:text-2xl font-handlee bg-black text-white px-4 py-2">Instagram</a>
                </div>
                <div class="flex items-center gap-4 justify-center pt-6 md:pt-10">
                    <p class="text-lg md:text-2xl font-handlee">© {{ year }} Zainab Nisa</p>
                </div>
            </div>
        </div>
    </div>
</template>