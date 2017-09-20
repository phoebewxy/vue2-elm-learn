<template>
    <div>

    </div>
</template>
<script>
    import headTop from '../../components/header/head.vue'
    export default {
        data() {
            return {
                guessCity: '',
                guessCityid: '',
                hotcity: [],
                groupcity: {}
            }
        },
        methods: {
            reload() {
                window.location.reload();
            }
        }
    }
</script>
<style scoped>

</style>

