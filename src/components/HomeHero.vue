<template>
    <v-container fluid fill-height class="home-hero">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center outline">SZCZELNICA</div>
            <div class="display-1 font-weight-bold white--text text-xs-center"></div>

        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background: url('https://images.unsplash.com/photo-1577905027671-c5cc33c825ed?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80');
    background-size: cover;
    width: 100%;
    height: 100%;
}
.outline {
    text-shadow: 4px 4px 8px #000000;
}
</style>