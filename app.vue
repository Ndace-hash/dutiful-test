<template>
  <main class="w-full max-w-[1220px] mx-auto  min-h-screen">
    <MobileHeader/>
    <DesktopHeader/>
    <section class="w-full">
      <NuxtPage/>
    </section>
    <Footer/>
  </main>
</template>

<script setup lang="ts">
  useHead({title: 'Dutiful website'})
</script>

