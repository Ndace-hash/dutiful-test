<template>
    <footer class="bg-primary px-4 md:px-12 py-4 md:py-8 z-0">
        <section class="py-6 flex flex-col md:flex-row md:justify-between">
            <div class="mb-4 flex flex-col gap-2">
                <h3 class="text-white text-lg font-semibold capitalize">company</h3>
                <ul class="flex flex-col gap-1">
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">about</NuxtLink>
                    </li>
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">contact us</NuxtLink>
                    </li>
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">FAQs</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="mb-4 flex flex-col gap-2">
                <h3 class="text-white text-lg font-semibold capitalize">quick links</h3>
                <ul class="flex flex-col gap-1">
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">find services</NuxtLink>
                    </li>
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">pricing & plans</NuxtLink>
                    </li>
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">list your business</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="mb-4 flex flex-col gap-2">
                <h3 class="text-white text-lg font-semibold capitalize">resources</h3>
                <ul class="flex flex-col gap-1">
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">blog</NuxtLink>
                    </li>
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">affiliate program</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="mb-4 flex flex-col gap-2">
                <h3 class="text-white text-lg font-semibold capitalize">more from dutiful</h3>
                <ul class="flex flex-col gap-1">
                    <li class="capitalize text-secondary text-sm">
                        <NuxtLink to="/">dutiful jobs</NuxtLink>
                    </li>
                </ul>
            </div>
            <ul class="flex md:hidden text-secondary capitalize text-sm justify-between items-center mt-2">
                <NuxtLink to="/">terms of service</NuxtLink>
                <NuxtLink to="/">privacy policy</NuxtLink>
                <NuxtLink to="/">disclaimer</NuxtLink>
            </ul>
        </section>
        <section class="flex flex-col md:flex-row-reverse md:justify-between w-full text-white items-center gap-4 py-3">
            <div class="flex items-center gap-4 py-3  w-full md:justify-end">
                <h3 class="capitalize">download</h3>
                <div class="flex gap-2 items-center">
                    <IconApple width="30" height="30"/>
                    <IconPlay width="30" height="30"/>
                </div>
            </div>
            <div class="flex items-center gap-4 py-3  w-full">
                <h3 class="capitalize">follow us</h3>
                <div class="flex gap-2 items-center">
                    <IconFacebook width="30" height="30"/>
                    <IconInstagram width="30" height="30"/>
                    <IconTwitter width="30" height="30"/>
                    <IconYoutube width="30" height="30"/>
                    <IconLinkedin width="30" height="30"/>
                </div>
            </div>
        </section>
        <section class="text-white capitalize text-sm md:text-base flex items-center justify-center md:justify-start gap-16">
            <p>&copy; 2022 dutiful&reg;</p>
            <ul class="md:flex hidden text-secondary capitalize text-base gap-4 items-center mt-2 self-center">
                <NuxtLink to="/">terms of service</NuxtLink>
                <NuxtLink to="/">privacy policy</NuxtLink>
                <NuxtLink to="/">disclaimer</NuxtLink>
            </ul>

        </section>
    </footer>
</template>

