<template>
    <section class="flex flex-col lg:flex-row bg-[rgba(245,238,255,.7)]">
        <div class="relative overflow-hidden">
            <div class="absolute inset-x-0 top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full rounded-lg h-3/4 bg-primary z-[0]"></div>
            <img src="~/assets/images/phone.svg" alt="image of a phone" class="scale-105 lg:scale-150 translate-x-1/4 lg:translate-y-1/4">
        </div>
        <div>
            <ServiceCard v-for="(card, index) in cards" :content="card" :key="inject" class="card z-30 bg-[#ffffff]"/>
        </div>
    </section>
</template>

<script setup>


const cards = [{
    icon: resolveComponent('IconDiscover'),
    heading: 'get discovered',
    text:'Dutiful is more than just a business directory; it also enhances your web profile. The platform makes use of SEO techniques to boost each listing\'s performance in the SERPs, providing any business the chance to rank, regardless of how strong their current online presence is.'
},
{
    icon: resolveComponent('IconChat'),
    heading: 'instant chat',
    text: 'You\'ll be able to chat and send voice recordings with potential and existing customers, including managing your captured leads anytime, anywhere via the platform'
},
{
    icon: resolveComponent('IconQuotation'),
    heading: 'quotation',
    text: 'In addition to providing customers with access to information, offering customer quotations is very advantageous to the way you conduct your business. On Dutiful, you\'ll be able to send and receive quotation from customers - an important step in lead management.'
}]
</script>

<style>
.card {
    transform: scale(.9);
}
.card:nth-child(2) {
    transform: translateX(-5%) scale(.9);
    @apply lg:translate-x-[-7%]
}

</style>