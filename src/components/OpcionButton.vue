<template>
    <div class="texto"> 
        <h3>Opcion 1 {{opcion1}}</h3>
        <button class="btn btn-primary" v-on:click="opcion1='---CLICK---'">Opcion 1</button>
        <hr>
        <h3>Opcion 2 {{opcion2}}</h3>
        <button class="btn btn-primary" v-on:click="sumar">Opcion 2</button>
        <hr>
        <h3>Opcion 3 {{texto}}</h3>
        <button class="btn btn-primary" v-on:click="seleccion(opcion3)">Opcion 3</button>
        <hr>
        <h3>Opcion 4 {{texto}}</h3>
        <button class="btn btn-primary" v-on:click="seleccion(opcion4)">Opcion 4</button>
    </div>
</template>

<script>
export default {
    name: 'OpcionButton',
    data (){
        return {
            opcion1:"",
            opcion2:"",
            opcion3:"---Opcion-3---",
            opcion4:"---Opcion-4---",
            texto:""
        }
    },
    methods:{
        sumar: function(){
            this.opcion2 = Math.floor(Math.random() * 100);
        },
        seleccion: function(opcion){
            this.texto = opcion;
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