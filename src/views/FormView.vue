<template>
  <div>
    <h1>Formularios</h1>

    <form>
        <h2>Tipo texto</h2>
        <b-form-input type="text" v-model="texto"></b-form-input>
        <p>texto: {{texto}}</p>
        <h2>Tipo numero</h2>
        <b-form-input type="number"></b-form-input>
    </form>

  </div>
</template>

<script>
export default {
    name:'FormView',
    data(){
        return{
            texto:''
        }
    }
}
</script>

<style>

</style>