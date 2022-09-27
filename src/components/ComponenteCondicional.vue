
<template>
    <div>
        <div class="ComponenteCondicional"> 
            <div v-if="mostrar1">
                Texto Condicional v-if
            </div>
            <div v-show="mostrar2">
                Texto Condicional v-show
            </div>

            <div v-if="mostrar3">
                Texto Condicional v-if
            </div>
            <div v-else-if="!mostrar3">
                Texto Condicional v-else-if
            </div>

            <div v-if="mostrar4">
                Texto Condicional v-if
            </div>
            <div v-else>
                Texto Condicional v-else
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ComponenteCondicional',
    data (){
        return {
           mostrar1:true,
           mostrar2:true,
           mostrar3:false,
           mostrar4:false
        }
    }
}
</script> 

<style>
</style>