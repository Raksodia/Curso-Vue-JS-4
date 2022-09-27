<template>
  <div id="app">
      <div class="container">
        <div class="row">
          <NavegacionPrincipal/>
        </div>
        <CssDinamicas/>
        <MiComponente/>
        <DesplegarArreglo/>
        <DesplegarObjetos/>
        <ComponenteCondicional/> 
        <ScopedStyle/> 
        <ContenidoSitio/> 
      </div>
  </div>
</template>

<script>

import MiComponente from './components/MiComponente.vue'
import DesplegarArreglo from './components/DesplegarArreglo.vue'
import DesplegarObjetos from './components/DesplegarObjetos.vue'
import ComponenteCondicional from './components/ComponenteCondicional.vue'
import NavegacionPrincipal from './components/NavegacionPrincipal.vue'
import CssDinamicas from './components/CssDinamicas.vue'
import ScopedStyle from './components/ScopedStyle.vue'
import ContenidoSitio from './components/ContenidoSitio.vue'

export default {
  name: 'App',
  components: {
    NavegacionPrincipal,
    MiComponente,
    DesplegarArreglo,
    DesplegarObjetos,
    ComponenteCondicional,
    CssDinamicas,
    ScopedStyle,
    ContenidoSitio
  } 
}
</script>

<style>
</style>
