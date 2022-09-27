
<template>
    <div>
        <div class="DesplegarArreglo"> 
        {{colores[1]}}
        </div>
        <div>
            <ul>
                <li v-for="(color,index) in colores" v-bind:key="index">{{ color }}</li>
            </ul>    
        </div>
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