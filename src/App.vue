<template>
  <div id="app">
    <Display />
    <Increment />
  </div>
</template>

<script>
import Display from './components/Display.vue';
import Increment from './components/Increment.vue';
import store from './vuex/store';

export default {
  name: 'App',
  components: {
    Display,
    Increment
  },
  store: store
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
