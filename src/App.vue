<template>
  <div id="app">
    <h1>App View</h1>
    <basket title="Toms Basket Component"></basket>
  </div>
</template>

<script>
import Basket from './components/Basket'
export default {
  name: 'app',
  components: {
    Basket
  },
  mounted () {
    console.log('YO, App has loaded')
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
