<template>
<MyNavBar/>
<router-view/>
<MyFooter/>
</template>

<script>

import MyNavBar from './components/MyNavBar.vue' 
import MyFooter from './components/MyFooter.vue' 

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
