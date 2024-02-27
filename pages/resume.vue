<template>
    <div>
        <h2>The highlights as a web developer</h2>
        <table>
            <tr v-for="(item, index) in resumeContent" :key="index">
                <td class="pr-8 text-xs pb-2">{{ item.date }}</td>
                <td>{{ item.job }}</td>
            </tr>
        </table>
    </div>
</template>

<script>
export default {
    data() {
        return {
            resumeContent: [
                {
                    date: 'December 2023 - now',
                    job: 'Web Design & Development freelancer @ Sea Lion Web Design | Nuxt + Tailwind CSS + Github CI/CD',
                },
                {
                    date: 'September 2022 - now',
                    job: 'Frontend Engineer @ ING | JS + Lit',
                },
                {
                    date: 'June 2022',
                    job: 'Workshop creator @ JS Nation | Nuxt 3 + Motion UI + Azure',
                },
                {
                    date: 'May 2021',
                    job: 'Speaker @ .BLD() Capgemini | Nuxt 2 + Edge computing + Azure',
                },
                {
                    date: 'Feb 2020 - August 2022',
                    job: 'Frontend Engineer @ ABN Amro | Vue 2 & 3 + Lit + Node + CSS-in-JS + Azure',
                },
                {
                    date: 'August 2019',
                    job: 'Frontend Engineer @ Atradius | RestAPIs + Oracle',
                },
                {
                    date: 'January 2019 - now',
                    job: 'Frontend Engineer @ Capgemini | Vue + Svelte + Nuxt + Storyblok CMS + AWS',
                },
                {
                    date: '2014 - 2018',
                    job: 'Copywriter & Social Media manager @ self-employed | Content creation + Copy',
                },
            ]
        }
    }
}
</script>