<template>
  <div id="app">
    <MiComponente/>
    <DesplegarArreglo/>
    <DesplegarObjetos/>
  </div>
</template>

<script>

import MiComponente from './components/MiComponente.vue'
import DesplegarArreglo from './components/DesplegarArreglo.vue'
import DesplegarObjetos from './components/DesplegarObjetos.vue'

export default {
  name: 'App',
  components: {
    MiComponente,
    DesplegarArreglo,
    DesplegarObjetos
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
