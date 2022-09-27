<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
<div class="container-fluid">
<a class="navbar-brand" href="#">Navbar</a>
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
        
        <NavegacionItem titulo="Inicio"/>
        <NavegacionItem titulo="Acerca"/>
        <NavegacionItem titulo="Tienda"/>
        <NavegacionItem titulo="Contacto"/>
        
        <NavegacionItem1 v-bind:navegacionData="{ titulo:'Inicio', url:'/Inicio'}"/>
        <NavegacionItem1 v-bind:navegacionData="{ titulo:'Acerca', url:'/Acerca'}"/>
        <NavegacionItem1 v-bind:navegacionData="{ titulo:'Tienda', url:'/Tienda'}"/>
        <NavegacionItem1 v-bind:navegacionData="{ titulo:'Contacto', url:'/Contacto'}"/>

    </ul>
</div>
</div>
 </nav>
</template>

<script>
import NavegacionItem from './NavegacionItem.vue'
import NavegacionItem1 from './NavegacionItem1.vue'

export default {
    name: 'NavegacionPrincipal',
    components: {
        NavegacionItem,
        NavegacionItem1
    },
    data (){ 
        return {
          
        }
    }
}
</script>