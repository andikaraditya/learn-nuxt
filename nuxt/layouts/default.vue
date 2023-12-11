<template>
    <div>
        <header>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/products">Products</NuxtLink></li>
            </ul>
        </header>
        <div>
            <slot />
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
a {
    color: black;
    text-decoration: none;
}
.router-link-active {
    font-weight: bold;
}
</style>