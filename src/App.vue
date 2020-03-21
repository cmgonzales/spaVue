<template>
  <div id="app">
  <App-Nav></App-Nav>
   <app-button></app-button>
 
  <Hello/>

  </div>
</template>

<script>
import Nav from './components/nav'
import button from './components/button'


export default {
  components: {
    'App-Nav': Nav,
    'app-button': button,
 
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
