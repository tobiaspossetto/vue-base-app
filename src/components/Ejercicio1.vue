<template>
    <div>
        <input v-model="nombre" type="text" placeholder="ingrese nombre">
        <p>Su nombre es {{nombre}}</p>
    </div>
</template>

<script>
    export default {
        name: 'Ejercicio1',
  
  data: function(){
    return {
      nombre:""
    }
  },
  methods: {

    
  }
    }
</script>

<style lang="scss" scoped>

</style>