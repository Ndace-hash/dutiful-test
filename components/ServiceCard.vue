<template>
    <div class="flex flex-col shadow-lg rounded-lg py-4 px-2 gap-2">
        <component :is="content.icon"/>

        <h3 class="capitalize font-bold text-black">{{ content.heading }}</h3>
        <p class="text-xs">{{ content.text }}</p>
    </div>
</template>

<script>
export default {
    setup(props){
    },
    props:{
        content: Object
    }
}
</script>

