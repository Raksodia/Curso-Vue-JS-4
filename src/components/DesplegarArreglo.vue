<template>
    <div class="DesplegarArreglo"> 
       {{colores[1]}}
    </div>
</template>

<script>
export default {
    name: 'DesplegarArreglo',
    data (){
        return {
            colores : ["rojo","verde","amarillo"]
        }
    }
}
</script>

<style>
</style>