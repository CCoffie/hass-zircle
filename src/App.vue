<template>
  <div id="app">
    <z-canvas :views="$options.components"></z-canvas>
  </div>
</template>

<script>
import home from './components/home'
export default {
  components: {
    home
  },
  mounted () {
    this.$zircle.setView('home')
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700');
@import url('https://use.fontawesome.com/releases/v5.1.0/css/all.css');
</style>
