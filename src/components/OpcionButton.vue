<template>
    <div class="texto"> 
        <h3>Opcion 1 {{opcion}}</h3>
        <button class="btn btn-primary" v-on:click="opcion='---CLICK---'">Opcion 1</button>
    </div>
</template>

<script>
export default {
    name: 'OpcionButton',
    data (){
        return {
             opcion:""
        }
    }
}
</script>

<style scoped>
.texto {
    color:red;
    font-family: 'Courier New', Courier, monospace;
    font-size: 16px;
}
</style>