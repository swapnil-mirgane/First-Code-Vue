<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <AddCount/>
  <LoginPage/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AddCount from './components/Add.vue';
import LoginPage from './components/Login.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    AddCount,
    LoginPage
  
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
