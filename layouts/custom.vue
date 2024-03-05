<template>
    <div>
    <header class="shadow-sm bg-white">
        <div class="font-bold">NuxTi</div>
        
    </header>
    <div class="container mx-auto p-4">
        <slot />
    </div>

    <footer class="container mx-auto p-4 flex justify-between border-t-2">
        <nav class="flex gap-4">
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/contactus">Contact Us</NuxtLink>
            <NuxtLink to="/products">View Products</NuxtLink>
        </nav>
    </footer>
</div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>