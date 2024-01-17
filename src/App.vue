<script>

/*
    Importazione componente
*/
import AppHeader from './components/AppHeader.vue';

export default {
    data() {
        return { 
            count: 0 
        }
    },
    /*
        Dichiarazione dei componenti all'interno dell'oggetto
    */
    components: {

        AppHeader
    },
}
</script>

<template>
    <div>
        <!--
            Utilizzo del componente
        -->
        <AppHeader/>
        <h1>
            Ciao Ragazzi
        </h1>

        <p>
            {{ count }}
        </p>

        <button @click="count++">
            Incrementa count
        </button>
    </div>
</template>

<style scoped>

</style>
