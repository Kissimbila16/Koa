<template>  
  <ViewVue/>
  </template>
<script>
import ViewVue from './components/View.vue'
export default {
  name: 'App',
  components: {
    ViewVue
  }
}
</script>

<style global>
:root {
  --bg-opaco:rgba(236, 222, 222, 0.114);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}



</style>
