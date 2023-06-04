<template>
  <header class="justify-between items-center py-2 px-12 hidden md:flex z-30">
    <NuxtLink to="/" class="w-20 ">
      <img src="/logo.svg" alt="LOGO" class="w-full">
    </NuxtLink>
    <div class="flex gap-4 md:gap-10">
      <div class="flex items-center gap-4">
        <IconSearch width="20px" height="20px"/>
        <ul class="flex gap-3 items-center">
          <li class="capitalize text-black text-sm"><NuxtLink to="/">business directory</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">features</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">pricing</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">blog</NuxtLink></li>
        </ul>
      </div>
      <div class="flex gap-4 items-center">
        <NuxtLink to="/auth/login" class="capitalize font-semibold">login</NuxtLink>
        <NuxtLink to="/auth/register" class="capitalize font-semibold border-primary border-2 px-12 py-3 text-primary text-base rounded-lg">sign up</NuxtLink>
      </div>
    </div>
  </header>
</template>

