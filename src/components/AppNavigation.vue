<template>
    <v-toolbar dark max-height="64">
            <v-toolbar-side-icon></v-toolbar-side-icon>
            <v-toolbar-title >{{appTitle}}</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn depressed color="blue-grey darken-1">Zaloguj</v-btn>
            <v-btn depressed color="blue-grey lighten-2">Zarejestruj się</v-btn>
            
        </v-toolbar>
</template>

<script>
export default {
    name: 'AppNavigation',
    data() {
        return{
            appTitle: 'Shooting Range'
        }
    }
};
</script>

<style scoped>
.v-toolbar-title{
    font-size: 10px;
}
</style>