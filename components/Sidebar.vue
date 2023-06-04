<template>
    <div class="bg-black absolute inset-0 bg-opacity-50 backdrop-blur-sm flex justify-end z-[40]" @click="$emit('close')">
        <ul class="bg-white h-full w-3/4 rounded-lg flex flex-col items-center justify-center gap-6">
            <li class="text-xl font-semibold capitalize">
                <NuxtLink to="/">Business directory</NuxtLink>
            </li>
            <li class="text-xl font-semibold capitalize">
                <NuxtLink to="/">features</NuxtLink>
            </li>
            <li class="text-xl font-semibold capitalize">
                <NuxtLink to="/">Pricing</NuxtLink>
            </li>
            <li class="text-xl font-semibold capitalize">
                <NuxtLink to="/">blog</NuxtLink>
            </li>
            <div class="flex flex-col gap-4 items-center mt-4">
                <NuxtLink to="/auth/login"
                    class="capitalize font-bold text-2xl border-primary border-2 px-12 py-2  w-full text-primary text-center rounded-lg">
                    login</NuxtLink>
                <NuxtLink to="/auth/register"
                    class="capitalize font-semibold border-primary bg-primary border-2 px-12 py-3 text-[#ffffff] text-2xl w-full rounded-lg">
                    sign up</NuxtLink>
            </div>
        </ul>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>