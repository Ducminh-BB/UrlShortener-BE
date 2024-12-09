<template>
  <div id="app">
    <nav></nav>
    <UrlView ></UrlView>
  </div>
</template>

<script>
  // import HelloWorld from './components/HelloWorld.vue'
  import UrlView from './components/UrlView.vue';


  export default {
    name: 'App',
    components: {
      UrlView
    },
  }
 
    
</script>

<style>
    /* #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  } */

    /* #app {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
  } */

    body {
      background-color: grey;
    }
</style>
