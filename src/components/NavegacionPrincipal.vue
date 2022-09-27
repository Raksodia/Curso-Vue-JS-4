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

    </ul>
</div>
</div>
 </nav>
</template>

<script>
import NavegacionItem from './NavegacionItem.vue'

export default {
    name: 'NavegacionPrincipal',
    components: {
        NavegacionItem
    },
    data (){ 
        return {
          
        }
    }
}
</script>