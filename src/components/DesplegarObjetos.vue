
<template>
    <div>
        <div class="DesplegarObjetos"> 
            <div v-for="(color,index) in colores" v-bind:key="index">
                {{color.nombre}} - {{color.nombreIngles}}
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'DesplegarObjetos',
    data (){
        return {
            colores : [{nombre:"rojo", nombreIngles:"red"},
            {nombre:"verde", nombreIngles:"green"}, 
            {nombre:"amarillo", nombreIngles:"yellow"},
            {nombre:"azul", nombreIngles:"blue"}
            ]
        }
    }
}
</script>

<style>
</style>