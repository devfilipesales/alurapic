<template>
  <div class="">
    <h1>{{ titulo }}</h1>
    <img :src="foto.url" :alt="foto.titulo">
  </div>
</template>

<script>
export default {
  data(){
    return {
      titulo: 'Alurapic',
      foto: {
        url: 'https://static.turbosquid.com/Preview/001230/434/2U/3D-wing-gundam-zero-custom-model_Z.jpg',
        titulo: 'Gundam'
      }
    }
  }
}
</script>

<style>

</style>
