<template>
    <div class="mx-auto container flex justify-around py-3 bg-black">
        <div class="logo w-20 h-20">
            <img src="../assets/images/logo.png" alt="">
        </div>
        <div class="menu">
            <ul>
                <li class="text-white inline-block p-3 text-xl font-black"><nuxt-link to="/">Home</nuxt-link></li>
                <li class="text-white inline-block p-3 text-xl font-black"><nuxt-link to="/about">About</nuxt-link></li>
                <li class="text-white inline-block p-3 text-xl font-black"><nuxt-link to="/contact">Contact</nuxt-link></li>

            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AirfareHeader'
}
</script>

<style>

</style>
