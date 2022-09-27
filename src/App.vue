<template>
  <div id="app">
    <MiComponente/>
    <DesplegarArreglo/>
    <DesplegarObjetos/>
    <ComponenteCondicional/>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
