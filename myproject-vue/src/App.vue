<template>
  <section>
    <MyNavBar/>
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
  }
}
</script>

<style>

</style>
