<template>
  <div id="app">
    <Index @dialog="true"/>
  </div>
</template>

<script>
import Index from './components/Index.vue'

export default {
  name: 'App',
  components: {
    Index,
  },
  // mounted(){
  //   const list = this.Tmdb;
  //   console.log('AQUI VAI RENDERIZAR A LIST', list)
  // }
}
</script>

<style>
#app{
  box-sizing: border-box;
}
</style>

