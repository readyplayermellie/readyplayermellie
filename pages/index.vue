<template>
    <div>
        <h1>{{ title }}</h1>
        <p class="leading-6 mb-4">I like to design and create websites, solve puzzles and share my knowledge with others. For the past five years I've been gladly doing this as a frontend developer consultant in the financial world, working mostly with Vue, Nuxt, Lit Element, NodeJS & Azure.</p>
        <p class="mb-4">I am honored to see you here and I'd like to tell you more about me as a:</p>
        <button class="mr-3"><NuxtLink href="/developer">Developer</NuxtLink></button>
        <button class="mr-3"><NuxtLink href="/human">Human</NuxtLink></button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Hi, I\'m Melanie the web developer'
        }
    }
}
</script>

<style scoped>
</style>