<template>
    <div class="OthersEvents"> 
        Others Events {{estado}}
        <input @keypress="estado='teclado'" @keypress.enter="estado='teclado enter'">
        <a v-on:click="estado='click'" v-on:mouseover="estado='onmouseover'"  class="btn btn-sucess">Click</a>
    </div>
</template>

<script>
export default {
    name: 'OthersEvents',
    data (){
        return { 
            estado:""
        }
    },
}
</script>

<style scoped>
.texto {
    color:red;
    font-size: 16px;
}
</style>