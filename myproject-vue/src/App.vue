<template>
  <section>
    <MyNavBar :logo="logo_src" :alt="app_name"/>
    <router-view/>
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
  },
  data() {
    return {
      logo_src: "/img/logo.png",
      app_name: "Make Your Burger",
    }
  },
}
</script>

<style>
  * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container {
    margin: 50px;
    min-height: 250px; 
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }

</style>
