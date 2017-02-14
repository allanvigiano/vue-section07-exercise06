<!--Server.vue - Created by allan-->
<template>
    <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
            <li class="list-group-item"  v-for="index in 5">
                Server #{{ index }}
            </li>
        </ul>
    </div>

</template>

<script>
    //import ComponentName from './componentPath';
    export default {
        data: function () {
            return {}
        },
        methods: {}
    }
</script>

<style>

</style>