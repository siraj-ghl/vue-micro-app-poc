<template>
  <div id="app">
    Siraj GHL
   <RemoteWidget />
  </div>
</template>

<script>
import RemoteWidget from 'vue3App/RemoteWidget';
export default {
  components: {
    RemoteWidget 
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
