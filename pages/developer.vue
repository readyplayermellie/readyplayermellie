<template>
    <div>
        <h2>{{ title }}</h2>
        <p class="mb-4">Once a freelance copywriter, now a corporate frontend developer: The switch that opened the doors to a career full of challenges and questions. I've appreciated this choice almost every day of the past 5+ years working as a developer.</p>
        <p class="mb-4">Programming provides me with infinite creativity and possibilities that I gladly explore besides my day job, which is why I've created Sea Lion Web Design, my development dreamland where I explore being a freelancer creating websites and offering my capabilities as a developer. With the freedom to choose the frameworks, languages and designs I find most fitting, I add a bit of extra spice to my knowledge and skill. Sea Lion Web Design will officially go live in Spring 2024.</p>
        <p class="mb-4">Click below to visit my Github page or open my resume (in English) in a new tab:</p>
        <div class="flex">
            <button class="mr-3"><a href="https://github.com/readyplayermellie" target="_blank">Go to my Github</a></button>
            <button><a href="/docs/en-resume.pdf" target="_blank">Preview my resume</a></button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'About Melanie the Web Developer',
        }
    }
}
</script>