<template>
  <div id="app">
     <AppMenu/>
    <Inicio/>
  </div>
</template>

<script>
import Inicio from './components/Inicio.vue'
import AppMenu from './components/AppMenu.vue'

export default {
  name: 'App',
  components: {
    Inicio,
    AppMenu
  }
}
</script>

<style>
#app {
  font-family: 'Segoe UI';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #64696B;
  margin-top: 10px;
}
</style>
