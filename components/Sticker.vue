<template>
    <NuxtLink class="group sticker w-96 flex" :to="content.link" :target="content.external ? '_blank' : '_self'">
        <img class="mr-4 group-hover:ml-2" src="~/assets/icons/alien.png">
        <p class="title">{{ content.title }}</p>
    </NuxtLink>
</template>

<script>
export default {
    props: {
        content: {
            title: String,
            subtitle: String,
            link: String,
            icon: String,
            external: Boolean
        }
    }
}
</script>

<style scoped>
</style>
