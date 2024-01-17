<script>
    export default {
        data() {
            return { 
                title: 'Ciao ragazzi' 
            }
        },
    }
    </script>

<template>
    <header class="main-title">
        <h1>
            {{ title }}
        </h1>
    </header>
</template>

<style scoped>
    h1{
        color: aquamarine;
        text-align: center;
    }
</style>
