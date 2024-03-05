<template>
    <div>
    <header class="shadow-sm bg-white">
        <div class="font-bold">NuxTi</div>
        <nav class="flex gap-4">
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/contactus">Contact Us</NuxtLink>
            <NuxtLink to="/products">View Products</NuxtLink>
        </nav>
    </header>
    <div class="container mx-auto p-4">
        <slot />
    </div>
</div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>