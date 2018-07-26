<template>
  <div id="app">
    <lotte-nav/>
    <app-nav/>

  </div>
</template>

<script>
import LotteNav from './components/LotteNav'
import AppNav from './components/AppNav'

export default {
  name: 'App',
  components: {
    LotteNav,AppNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
