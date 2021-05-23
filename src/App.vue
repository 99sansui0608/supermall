<template>
  <div id="app">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>

<script>
import MainTabBar from 'components/conteent/mainTabbar'

export default {
  name: 'App',
  components: {
   MainTabBar
   
  }
}
</script>

<style>
@import "assets/css/normalize.css";
</style>
