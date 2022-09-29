<template>
    <div class="EntradaTexto"> 
        Entrada Texto 
        <input v-bind:value="EntradaTexto"/>
    </div>
</template>

<script>
export default {
    name: 'EntradaTexo',
    data (){
        return {
            EntradaTexto:"*** Texto ***"
        }
    },
}
</script>

<style scoped>
.texto {
    color:red;
    
    font-size: 16px;
}
</style>