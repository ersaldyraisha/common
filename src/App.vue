<template>
  <div id="app">
    <ui-button>Elah</ui-button>
  </div>
</template>

<script>
import Button from './components/Button.vue'

export default {
  name: 'app',
  components: {
    uiButton: Button
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
