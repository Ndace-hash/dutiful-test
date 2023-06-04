<template>
    <div class="flex py-12 items-center justify-center w-full">
        <form class=" min-h-[200px] w-full max-w-[400px] mb-4">
            <span>Sign up for free</span>
            <h2 class="font-bold capitalize text-4xl mb-4 mt-2 text-dark-blue">Get started</h2>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="fullName" class="text-primary">Full name</label>
                <input type="text" name="fullName" id="fullName" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
            </div>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="email" class="text-primary">Email</label>
                <input type="email" name="email" id="email" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
            </div>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="phone" class="text-primary">Phone number</label>
                <input type="text" name="phone" id="phone" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
            </div>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="password" class="text-primary">Password</label>
                <input type="password" name="password" id="password" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
            </div>
            <div class="form-group flex flex-col gap-1 mb-6">
                <label for="confirm" class="text-primary">Re-enter password</label>
                <input type="password" name="confirm" id="confirm" class="border border-[#E7EAF1] bg-[#F8FAFD] py-2 px-3 focus:outline-primary">
                <div class="mt-2">
                    <input type="checkbox" name="termsAndConditions" id="tnc" class="outline-primary">
                    <label for="tnc"> I agree to Dutiful's <NuxtLink to="/" class="text-primary underline">terms and conditions</NuxtLink></label>
                </div>
            </div>
            <input type="submit" value="login" class="bg-primary w-full text-white capitalize text-base py-4 rounded-lg mb-6 font-semibold">
            <p class="text-secondary text-center">Already have an account? <NuxtLink to="/auth/login" class="text-primary font-semibold">Login</NuxtLink></p>
        </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>