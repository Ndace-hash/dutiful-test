<template>
    <div class="flex py-12 items-center justify-center w-full">
        <form class=" min-h-[200px] w-full max-w-[400px] mb-4">
            <span>Jump right back in</span>
            <h2 class="font-bold capitalize text-4xl mb-4 mt-2 text-dark-blue">Login</h2>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="email" class="text-primary">Email</label>
                <input type="email" name="email" id="email" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
            </div>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="password" class="text-primary">Password</label>
                <input type="password" name="password" id="password" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
                <NuxtLink to="/auth/login" class="text-primary text-right text-sm mt-2">Forgot password?</NuxtLink>
            </div>
            <input type="submit" value="login" class="bg-primary w-full text-white capitalize text-base py-4 rounded-lg mb-6 font-semibold">
            <p class="text-secondary text-center">Don't have an account? <NuxtLink to="/auth/register" class="text-primary font-semibold">Sign up</NuxtLink></p>
        </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>