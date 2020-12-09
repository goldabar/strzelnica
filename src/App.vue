<template>
    <v-app>
        <app-navigation></app-navigation>
        <home-hero></home-hero>

        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
</template>

<script>
import AppNavigation from './components/AppNavigation'
import HomeHero from './components/HomeHero.vue';

export default {
    name: 'App',
    components: {
        AppNavigation,
        HomeHero
    }
};
</script>

<style>
</style>