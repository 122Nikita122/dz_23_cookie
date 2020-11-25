<template>
  <div id="app">
    <Cookies/>
    
  </div>
</template>

<script>

import Cookies from './components/Cookies.vue'

export default {
  name: 'App',
  components: {
    Cookies
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
