<template>
  <div id="app">
    
    <!-- #4 เรียกใช้ component ตาม tag ที่ประกาศไว้ -->
    <todo-app>,</todo-app>
    
    
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import todoApp from './components/todoApp.vue'
//#2 import component


export default {
  name: 'App',
  components: {
    todoApp
    //#3 register component/ ประกาศตัวแปร tag <...>
    
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
