<template>
    <nav>
        <p class="mb-3">Where do you want to go?</p>
        <div class="w-2/5 flex justify-center flex-col">
            <Sticker v-for="content in stickerContent" :content="content"/>
        </div>
    </nav>
</template>

<script>
export default {
    data() {
        return {
            title: 'Ready Player Mellie',
            stickerContent: [
                {
                    title: 'Home',
                    link: '/',
                    external: false,
                },
                {
                    title: 'Developer',
                    link: '/developer',
                    external: false,
                },
                {
                    title: 'Human',
                    link: '/human',
                    external: false,
                },
                {
                    title: 'Resume',
                    link: '/resume',
                    external: false,
                },
                {
                    title: 'Contact me',
                    link: '/contact',
                    external: false,
                },
                {
                    title: 'Ori Under Way',
                    link: 'https://www.oriunderway.com',
                    external: true,
                }
            ]
        }
    }
}
</script>