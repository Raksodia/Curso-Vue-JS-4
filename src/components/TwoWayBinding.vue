<template>
    <div class="TwoWayBinding"> 
        Two Way Binding {{EntradaTexto}}
        <input v-model="EntradaTexto"/>
        <button class="btn btn-primary" v-on:click="EntradaTexto='Nuevo Texto'">Cambiar</button>
    </div>
</template>

<script>
export default {
    name: 'TwoWayBinding',
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