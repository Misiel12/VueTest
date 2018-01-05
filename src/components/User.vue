<template>
    <div id="user">
        <h3>The User</h3>
        <p>My username is {{ username }}</p>
        <app-info></app-info>
    </div>
</template>

<script>
    import Info from './Info.vue'
    export default {
        name: 'app',
        data () {
            return {
                username: 'Ali'
            }
        },
        components : {
            'app-info': Info
        }
    }
</script>

<style>
    p {
        font-style: italic;
    }
</style>
