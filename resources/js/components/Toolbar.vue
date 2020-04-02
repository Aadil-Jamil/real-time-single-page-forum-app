<template>
    <v-toolbar>
<!--        <v-toolbar-side-icon></v-toolbar-side-icon>-->
        <v-toolbar-title>Bitfumes</v-toolbar-title>
        <v-spacer></v-spacer>
        <div class="hidden-sm-and-down">
            <router-link to="/forum">
                <v-btn text>Forum</v-btn>
            </router-link>
<!--            <router-link>-->
                <v-btn text>Ask Question</v-btn>
<!--            </router-link>-->
<!--            <router-link>-->
                <v-btn text>Category</v-btn>
<!--            </router-link>-->
            <router-link to="/login">
                <v-btn text>Login</v-btn>
            </router-link>
        </div>
    </v-toolbar>
</template>

<script>

    export default {

    }
</script>

<style>

</style>
