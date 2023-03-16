<template>
  <section>
    <MyNavBar/>
    <MyFooter/>
  </section>
</template>

<script>
import MyNavBar from './components/MyNavBar.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  name: 'App',
  components: {
    MyNavBar,
    MyFooter,
  }
}
</script>

<style>
body {
  /* background-color: rgb(74, 30, 74); */
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
