<template>
    <div class="texto"> 
        Texto Contenido Sitio
        
        <OpcionButton/>
        <EntradaTexto/>
        <TwoWayBinding/>
    </div>
    
</template>

<script>
import OpcionButton from './OpcionButton.vue' 
import EntradaTexto from './EntradaTexto.vue' 
import TwoWayBinding from './TwoWayBinding.vue' 

export default {
    name: 'ContenidoSitio',
    data (){
        return {
             
        }
    },
    components: {
        OpcionButton,
        EntradaTexto,
        TwoWayBinding
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