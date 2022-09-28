<template>
    <div class="texto"> 
        Texto Contenido Sitio
        
        <OpcionButton/>
        
    </div>
    
</template>

<script>
import OpcionButton from './OpcionButton.vue' 

export default {
    name: 'ContenidoSitio',
    data (){
        return {
             
        }
    },
    components: {
        OpcionButton
    }
}
</script>

<style scoped>
.texto {
    color:red;
    font-family: 'Courier New', Courier, monospace;
    font-size: 12px;;
}
</style>