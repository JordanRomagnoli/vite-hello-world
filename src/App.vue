<script>

/*
    Importazione componente
*/
import AppTitle from './components/AppTitle.vue';

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

        AppTitle
    },
}
</script>

<template>
    <div>
        <!--
            Utilizzo del componente
        -->
        <AppTitle/>
        
    </div>
</template>

<style scoped>

</style>
