<template>
    <v-app id="app">
        <div class="container-fluid">
            <Header/>
            <Todos/>
        </div>
    </v-app>
</template>

<script>
    import Todos from './components/Todos';
    import Header from './components/Header';

    export default {
        name: 'App',
        components: {
            Todos,
            Header
        }
    }
</script>

<style>
    #app {
        padding: 0 15px;
        background-color: azure;
    }
</style>

