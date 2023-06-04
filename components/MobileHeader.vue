<template>
  <header class="flex items-center justify-between px-[30px] py-4 md:hidden">
    <NuxtLink to="/" class="flex items-center justify-center w-20">
      <img src="/logo.svg" alt="LOGO" class="w-full">
    </NuxtLink>
    <button class="py-4 px-3 flex flex-col gap-3 items-center justify-center z-50" @click="toggleNav">
      <span :class="['min-w-[40px] w-full min-h-[3px] bg-primary block rounded-full ease-in duration-200',showNav ? 'rotate-45 translate-y-2 translate-x-1' : '']"></span>
      <span :class="['min-w-[40px] w-full min-h-[3px] bg-primary block rounded-full ease-in duration-200',showNav ? '-rotate-45 translate-x-1 -translate-y-2' : '']"></span>
    </button>
    <Sidebar :class="['absolute ease-in duration-1000', showNav ? 'translate-x-0 block opacity-100' : 'translate-x-full hidden opacity-0']" @close="showNav = false"/>
  </header>
</template>

<script setup>
  const showNav = ref(false)
  const toggleNav = () => {
    showNav.value = !showNav.value
  }
</script>