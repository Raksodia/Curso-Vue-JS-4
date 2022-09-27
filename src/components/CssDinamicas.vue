<template>
    <div class="CssDinamicas"> 
        <div v-bind:style="{ backgroundColor: colorRandom}">
        CSS Dinamicas
        </div>
    </div>
</template>

<script>
export default {
    name: 'CssDinamicas',
    data (){
        return {
             colorRandom : "#"+Math.floor(Math.random()*6777215).toString(16)
        }
    }
}
</script>

<style>
</style>