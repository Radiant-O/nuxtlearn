<template>
    <div>
        <p>{{ product.title }}</p>
        <p>{{ product.price }}</p>
        <p>{{ product.description }}</p>
        <p>{{ product.id }}</p>
    </div>
</template>

<script setup>
import { useRoute } from 'vue-router';

const { id } = useRoute().params

const url = `https://fakestoreapi.com/products/${id}`

    const { data: product} = await useFetch(url, { key: id})

definePageMeta({
        layout:'custom'
    })

</script>

<style lang="scss" scoped>

</style> 