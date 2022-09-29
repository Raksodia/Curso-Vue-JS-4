<template>
    <div class="EntradaTexto"> 
        Entrada Texto 
        <input v-bind:value="EntradaTexto"/>
        <button class="btn btn-primary" v-on:click="EntradaTexto='Nuevo Texto'">Cambiar</button>
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