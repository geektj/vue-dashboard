<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png"> -->
   <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> props passed in this components output in helloword file -->
   <Dashboard />
  </div>
</template>

<script>
import Dashboard from './components/Dashboard.vue'


export default {
  name: 'App',
  components: {
    Dashboard
  }
}
</script>
 
<style>
*{
    margin: 0px;
    padding: 0px;
}


</style>
