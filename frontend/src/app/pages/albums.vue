<template>
    <v-container fluid>
        <h1 class="md-display-1">Albums</h1>
        <p class="md-subheading">
            A user-friendly tool for importing, filtering and archiving large amounts of JPEG and RAW files
        </p>
    </v-container>
</template>

<script>
    export default {
        name: 'browse',
        data() {
            return {
            };
        },
        methods: {
        }
    };
</script>

<style scoped>
    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }
</style>
