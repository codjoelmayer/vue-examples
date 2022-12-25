<template>
  <h2>Two way binding</h2>
  <DataBindingComp/>
</template>

<script>

import DataBindingComp from './components/DataBindingComp.vue';
export default {
  name: 'App',
  components: {
    DataBindingComp
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
