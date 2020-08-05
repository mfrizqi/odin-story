<template>
  <div id="app">
    <WholePage/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import WholePage from './components/WholePage.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    WholePage
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Rowdies:wght@300;400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700&display=swap');

body{
  margin: 0 15vw 0 15vw;
  padding: 0;
}

#app {
  font-family: 'Open Sans';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
