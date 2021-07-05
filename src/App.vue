<template>
  <div id="app">
    <SimpleView />
  </div>
</template>

<script>
import SimpleView from './components/SimpleView.vue'

export default {
  name: 'App',
  components: {
    SimpleView
  }
}
</script>

<style>
html,
body,
#app {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
