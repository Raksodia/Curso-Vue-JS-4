<template>
    <div class="texto"> 
        <h3>Opcion 1 {{opcion1}}</h3>
        <button class="btn btn-primary" v-on:click="opcion1='---CLICK---'">Opcion 1</button>
        <hr>
        <h3>Opcion 2 {{opcion2}}</h3>
        <button class="btn btn-primary" v-on:click="sumar">Opcion 2</button>
    </div>
</template>

<script>
export default {
    name: 'OpcionButton',
    data (){
        return {
             opcion1:"",
             opcion2:""
        }
    },
    methods:{
        sumar: function(){
            this.opcion2 = Math.floor(Math.random() * 100);
        }
    }
}
</script>

<style scoped>
.texto {
    color:red;
    
    font-size: 16px;
}
</style>