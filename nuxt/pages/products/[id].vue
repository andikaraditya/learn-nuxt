<template>
    <div>
        <h1>Hello Product</h1>
        <h2>Id: {{ id }}</h2>
    </div>
</template>

<script setup>
    const {id} = useRoute().params

    definePageMeta({
        layout: "products"
    })
</script>

<style scoped>

</style>