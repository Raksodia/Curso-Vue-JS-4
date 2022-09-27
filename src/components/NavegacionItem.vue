    <template>
    <li class="nav-item">
        <a class="nav-link" v-bind:style="{ backgroundColor: colorRandom}" v-bind:class="{active:mostrarActivo}" aria-current="page" href="#">Link</a>
    </li>
</template>

<script>
export default {
    name: 'NavegacionItem',
    data (){
        return {
            mostrarActivo: true,
            colorRandom : "#"+Math.floor(Math.random()*6777215).toString(16)
        } 
    }
}
</script>

<style>
</style>