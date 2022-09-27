<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
<div class="container-fluid">
<a class="navbar-brand" href="#">Navbar</a>
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
        
        <NavegacionItem2 v-bind:key="index" v-bind:navegacionData="item" v-for="(item,index) in ItemsNavegacion" />
    </ul>
</div>
</div>
 </nav>
</template>

<script>
import NavegacionItem2 from './NavegacionItem2.vue' 

export default {
    name: 'NavegacionSecundaria',
    components: {
        NavegacionItem2
    },
    data (){ 
        return {
          ItemsNavegacion: [
            {
                titulo:"Inicio",
                url:"/Inicio"
            },
            {
                titulo:"Acerca",
                url:"/Acerca"
            },
            {
                titulo:"Tienda",
                url:"/Tienda"
            },
            {
                titulo:"Contacto",
                url:"/Contacto"
            }
          ]
        }
    }
}
</script>