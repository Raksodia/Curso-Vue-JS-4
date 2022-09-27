<template>
    <li class="nav-item">
        <a class="nav-link" v-bind:style="{ backgroundColor: colorRandom}" v-bind:class="{active:mostrarActivo}" aria-current="page" v-bind:href="navegacionData.url">{{navegacionData.titulo}}</a>
    </li>
</template>

<script>
export default {
    name: 'NavegacionItem2',
    data (){
        return {
            mostrarActivo: true,
            colorRandom : "#"+Math.floor(Math.random()*6777215).toString(16)
        } 
    },
    props:{
        navegacionData: Object
    }
}
</script>

<style>
</style>