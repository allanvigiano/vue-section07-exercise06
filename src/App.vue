<template>
    <div class="container">


        <header-cmp></header-cmp>
        <hr>

        <div class="row">
            <servers-cmp></servers-cmp>
            <details-cmp></details-cmp>
        </div>
        <hr>
        <footer-cmp></footer-cmp>
    </div>
</template>

<script>
    import Servers from './Servers.vue';
    import Header from './Header.vue';
    import Footer from './Footer.vue';
    import Details from './Details.vue';
    export default {
        components: {
            serversCmp: Servers,
            headerCmp: Header,
            footerCmp: Footer,
            detailsCmp: Details,
        },
        data: function () {
            return {}
        },
        methods: {}
    }
</script>

<style>

</style>
