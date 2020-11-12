<template>
    <div class="mx-auto">
        <div class="mt-24">
            <nav class="p-2 py-2 flex flex-1 mt-4">
                <div class="flex flex-1 justify-end content-center text-gray-700 mr-8">
                    <NuxtLink to="/" class="">Home</NuxtLink>
                    <NuxtLink to="/projects" class="mx-4">Projects</NuxtLink>
                    <NuxtLink to="/about" class="mr-4">About</NuxtLink>
                    <NuxtLink to="#" class="mr-4">Hire me!</NuxtLink>
                </div>
            </nav>

            <nuxt></nuxt>

            <NuxtLink to="/about">About page</NuxtLink>

        </div>
    </div>
</template>

<style>
    .mono {
        font-family: 'Source Code Pro', monospace;
    }

    .nuxt-link-exact-active{
        color: #f687b3;
    }
</style>
