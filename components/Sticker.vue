<template>
    <NuxtLink class="group sticker w-96 flex" :to="content.link" :target="content.external ? '_blank' : '_self'">
        <img class="nav-arrow mr-4 group-hover:ml-2" src="../assets/icons/right-arrows.png">
        <p class="title">{{ content.title }}</p>
    </NuxtLink>
</template>
<script>
// TODO:
// [ ] Turn the sticker into a clickable big button
// [ ] Create an effect where the sticker turns around to the subtitle on hover
// [ ] Add a link to the sticker to open some content just below the header

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

.nav-arrow {
    width: 25px;
}
</style>