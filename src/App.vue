<template>
  <div id="app">
    <app-header></app-header>

      <app-home></app-home>

      <app-menu></app-menu>

      <app-admin></app-admin>
    
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
//import Home from './components/Home.vue'
import Footer from './components/Footer.vue'

//import Menu from './components/Menu.vue'

import Admin from './components/Admin.vue'

export default {
  name: 'app',
  components: {
    appHeader: Header,
//    appHome: Home,
//    appMenu: Menu,   
    appFooter: Footer,

    appAdmin: Admin
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
  margin-top: 60px;
}

</style>
