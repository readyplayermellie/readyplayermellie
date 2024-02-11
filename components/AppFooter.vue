<template>
    <div class="footer h-10">
        <p class="text-center">{{ content }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            content: 'Made with Nuxt, Tailwind CSS & Love'
        }
    }
}
</script>

<style scoped>
.footer {
    margin-top: -36px;
}
</style>