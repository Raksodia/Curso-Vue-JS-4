<template>
    <div class="MiComponente"> 
        <h1>Mi Componente Funciona</h1>
        <h3>{{libro.titulo}}</h3>
        <h4>{{libro.autor}}</h4>
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data (){
        return {
            libro : {
                autor: "Autor",
                titulo: "Titulo"
            } 
        }
    }
}
</script>

<style>
</style>