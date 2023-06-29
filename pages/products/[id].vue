<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">NUXT DOJO</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum doloribus voluptates officiis asperiores accusantium quam.</p>
    </div>
</template>

<script setup>

const {id} = useRoute().params

</script>

<style scoped>

</style>