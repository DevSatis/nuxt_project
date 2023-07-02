<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/products">NUXT DOJO</NuxtLink>
            </nav>
        </header>
        <div>
            <slot/>
        </div>
        <footer>
             <ul>
                <li>@Cambridge, all copy right reserved!</li>
                <li>2023, new pages</li>
             </ul>
        </footer>
    </div>
</template>

<style scoped>
footer > ul{
    list-style-type: none;
    display: flex;
    justify-content: space-between;
}

</style>