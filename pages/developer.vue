<template>
    <div>
        <h2>{{ title }}</h2>
        <p class="leading-6 mb-3">Web Development in all its glory is my passion. That is why I am not only working as a frontend developer in the Financial World, but I also have my own company. With Sea Lion Web Design I design and create websites, but I can also dive into the harder to solve tasks like setting up your professional email accounts, connecting domains and adding a bit of functionality to your news letters. <a href="https://wwww.sealionwebdesign.com" class="text-sky-950">Read more about Sea Lion Web Design</a></p>
        <p class="leading-6 mb-4">My big dream in life is to one day sail the world - or at least to the Mediterranean with my own sailboat. To learn how to live with less, live aboard fulltime and to recharge my relationship with the world and nature. We have found our sailboat and are busy with the preparations for this adventure. You can take a look at <a href="https://www.oriunderway.com" class="text-sky-950">our sailing blog Ori Under Way</a> for updates and content!</p>
        <div class="flex">
            <button class="mr-3"><a href="https://github.com/readyplayermellie">Go to my Github</a></button>
            <button><a href="/docs/cv.pdf" target="_blank">Preview my resume</a></button>
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