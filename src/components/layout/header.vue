<template>
    <div class="header">
        <a class="item home">Ronal BLog</a>
        <a class="item">Search</a>
        <a class="item">About</a>
        <a class="item">Archieve</a>
        <a class="item">Tags</a>
        <a class="item">Categories</a>
    </div>
</template>

<script lang="ts">
    import Vue from 'vue'

    export default Vue.extend({
        
    })
</script>

<style scoped>
    .header{
        position: fixed;
        top: 0;
        width: 100vw;
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        align-items: center;
        height: 50px;
    }

    .home{
        flex-grow: 1;
    }
    .item{
        display: block;

    }
</style>