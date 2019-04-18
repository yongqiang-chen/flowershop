<template>
  <div id="app">
    <app-header></app-header>
    <router-view/>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from './components/common/header/Header';
import AppFooter from './components/common/footer/Footer';
export default {
  name: 'App',
  components:{
    AppHeader,
    AppFooter
  }
}
</script>

<style>

</style>
