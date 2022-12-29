<template>
  <main class="container-fluid">
    <VIfComponent/>
    <VShowComponent/>
  </main>
</template>

<script>
import VIfComponent from './components/V-ifComponent.vue';
import VShowComponent from './components/V-ShowComponent.vue';
export default {
  name: 'App',
  components:{
    VIfComponent,
    VShowComponent
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
