<template>
<div>
    <svg :width="width" :height="height" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
    <circle cx="19.6108" cy="19.611" r="14.9809" stroke="#603F8B" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M30.0303 30.8086L35.9037 36.6667" stroke="#603F8B" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
</div>
</template>

<script setup lang="ts">
    defineProps({
        width: {
            type: String,
            default: 40

        },
        height: {
            type: String,
            default: 40
        }
    })
</script>
