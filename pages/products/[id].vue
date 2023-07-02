<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum doloribus voluptates officiis asperiores accusantium quam.</p>
    </div>
</template>

<script setup>

const {id} = useRoute().params

definePageMeta({
        layout:'footer-for-pages'
    })

</script>

<style scoped>

</style>