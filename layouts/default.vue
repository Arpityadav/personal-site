<template>
    <div class="mx-auto">
        <sidebar-menu :menu="menu" :collapsed="true"/>
        <div class="mt-24">
<!--            <nav class="p-2 py-2 flex flex-1 mt-4">-->
<!--            </nav>-->

            <nuxt></nuxt>
        </div>
    </div>
</template>

<script>
    import { SidebarMenu } from 'vue-sidebar-menu'

    export default {
        data() {
            return {
                menu: [
                    {
                        header: true,
                        title: 'MENU',
                        hiddenOnCollapse: true
                    },
                    {
                        href: '/',
                        title: 'Home',
                        icon: 'fas fa-home'
                    },
                    {
                        href: '/projects',
                        title: 'My Projects',
                        icon: 'fab fa-app-store-ios'
                    },
                    {
                        href: '/about',
                        title: 'About',
                        icon: 'fas fa-address-card'
                    },
                ]
            }
        },

        components: {
            SidebarMenu
        }
    }
</script>

<style>
    .mono {
        font-family: 'Source Code Pro', monospace;
    }

    .nuxt-link-exact-active{
        color: #f687b3;
    }
</style>
