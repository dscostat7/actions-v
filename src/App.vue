<template>
<div class="container">
  <h1 v-text="titulo"></h1>
  <img :src="foto.url" :alt="foto.titulo">
</div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'ActionsV',
      foto: {
        url: 'https://2.bp.blogspot.com/-JIoop1fMtqQ/Vujbq6UIFBI/AAAAAAAAQ0Q/6Cx30EPjKfsun2fItwznBZk8fROnGyGGA/s1600/banner.jpg',
        titulo: 'cmaismais'
      }
    }
  }
}
</script>

<style>

</style>
