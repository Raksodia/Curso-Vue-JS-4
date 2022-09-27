<template>
  <div id="app">
      <div class="container">
        <div class="row">
          <NavegacionPrincipal/>
        </div>
        <MiComponente/>
        <DesplegarArreglo/>
        <DesplegarObjetos/>
        <ComponenteCondicional/>
      </div>
  </div>
</template>

<script>

import MiComponente from './components/MiComponente.vue'
import DesplegarArreglo from './components/DesplegarArreglo.vue'
import DesplegarObjetos from './components/DesplegarObjetos.vue'
import ComponenteCondicional from './components/ComponenteCondicional.vue'
import NavegacionPrincipal from './components/NavegacionPrincipal.vue'

export default {
  name: 'App',
  components: {
    NavegacionPrincipal,
    MiComponente,
    DesplegarArreglo,
    DesplegarObjetos,
    ComponenteCondicional,
   
  } 
}
</script>

<style>
</style>
