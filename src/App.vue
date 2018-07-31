<template>
  <div id="app">
    <lotte-nav/>
    <app-nav/>
    <about/>
    <benefit/>
    <contact-form/>
    <app-footer/>
  </div>
</template>

<script>
import LotteNav from './components/LotteNav'
import AppNav from './components/AppNav'
import About from './components/About'
import Benefit from './components/Benefit'
import ContactForm from './components/ContactForm'
import AppFooter from './components/AppFooter'

export default {
  name: 'App',
  components: {
    LotteNav,AppNav,About,Benefit,ContactForm,AppFooter
  }
}
</script>

<style>
@import url(https://fonts.googleapis.com/css?family=ABeeZee);
#app {
  font-family: 'ABeeZee', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 0px;
  height: auto;
  width: auto;
}
</style>
