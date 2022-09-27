<template>
  <div id="app">
      <div class="container">
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

export default {
  name: 'App',
  components: {
    MiComponente,
    DesplegarArreglo,
    DesplegarObjetos,
    ComponenteCondicional
  } 
}
</script>

<style>
</style>
