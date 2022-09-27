<template>
    <div class="MiComponente"> 
        <h1>{{libro.titulo}}</h1>
        <h2>{{libro.autor}}</h2>
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