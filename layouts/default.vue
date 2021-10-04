<template>
    <div class="mx-auto">
        <div class="my-8">
            <nav class="p-2 py-2 flex flex-1 mt-4">
                <div class="flex flex-1 justify-end content-center text-gray-700 mr-8">
                    <NuxtLink to="/" class="">Home</NuxtLink>
                    <NuxtLink to="/projects" class="mx-4">Projects</NuxtLink>
                    <NuxtLink to="/about" class="mr-4">About</NuxtLink>
                    <a target="_top" href="mailto:hey_arpit@outlook.com">Hire me!</a>
                </div>
            </nav>
            <div class="md:grid md:grid-cols-11 gap-0 mb-10 mt-12">
                <div class="md:col-start-4 md:col-end-9 mx-12">
                    <div class="border-b flex pb-10">
                        <img src="~/assets/me.jpeg" alt="" class="border rounded-full w-32">
                        <div class="flex flex-col items-start justify-center ml-8">
                            <h2 class="text-3xl">Arpit&nbsp;Yadav</h2>
                            <p class="text-gray-600 text-lg">Software&nbsp;Developer</p>
                        </div>
                    </div>
                </div>
            </div>

            <nuxt></nuxt>
        </div>
    </div>
</template>

<style>
.mono {
    font-family: 'Source Code Pro', monospace;
}
    ::selection {
        color: white;
        background: #5c6ac4;
    }

.nuxt-link-exact-active {
    color: #5c6ac4;
}
</style>
