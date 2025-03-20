<script>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="flex text-center justify-between bg-gray-600 py-4 px-8 item-center">

        <div class="flex items-center">
            <img class="w-16 h-16"
                src="https://bcassetcdn.com/assets/images/designcom/maker-home-v2/how-logo-step-2.webp" alt="">
            <p class="text-white text-3xl font-bold">Apa aja</p>
        </div>

        <div class="flex gap-20">
            <RouterLink class="text-white text-2xl" to="/home">home</RouterLink>
            <RouterLink class="text-white text-2xl" to="/about">About</RouterLink>
            <RouterLink class="text-white text-2xl" to="/projek">projek</RouterLink>
            <RouterLink class="text-white text-2xl" to="/kontak">kontak</RouterLink>
        </div>
    </div>
</template>