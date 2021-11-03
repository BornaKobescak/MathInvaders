<template>
  <div id="app">
    
    <AddInput msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import AddInput from './components/AddInput.vue'

export default {
  name: 'App',
  components: {
    AddInput
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

