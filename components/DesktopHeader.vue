<template>
  <header class="justify-between items-center py-2 px-12 hidden md:flex">
    <div class="w-20 ">
      <img src="/logo.svg" alt="LOGO" class="w-full">
    </div>
    <div class="flex gap-4">
      <div class="flex items-center gap-4">
        <IconSearch width="20px" height="20px"/>
        <ul class="flex gap-3 items-center">
          <li class="capitalize text-black text-sm"><NuxtLink to="/">business directory</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">features</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">pricing</NuxtLink></li>
          <li class="capitalize text-black text-sm"><NuxtLink to="/">blog</NuxtLink></li>
        </ul>
      </div>
      <div class="flex gap-4">
        <button class="capitalize font-semibold">login</button>
        <button class="capitalize font-semibold border-primary border-2 px-12 py-3 text-primary text-base rounded-lg">sign up</button>
      </div>
    </div>
  </header>
</template>

