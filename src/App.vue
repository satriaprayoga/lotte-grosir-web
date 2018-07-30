<template>
  <div id="app">
    <lotte-nav/>
    <app-nav/>
    <contact-form/>

  </div>
</template>

<script>
import LotteNav from './components/LotteNav'
import AppNav from './components/AppNav'
import ContactForm from './components/ContactForm'

export default {
  name: 'App',
  components: {
    LotteNav,AppNav,ContactForm
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
  height: auto;
}
</style>
