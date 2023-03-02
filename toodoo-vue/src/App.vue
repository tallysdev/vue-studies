<template lang="">

  <div>
    <h1>Tallys</h1>
  </div>
  <MyFirstComponents/>
  <MyLifeCycle/>
  <MyPerson/>

</template>

<script>

import MyFirstComponents from './components/MyFirstComponents.vue';
import MyLifeCycle from './components/MyLifeCycle.vue';
import MyPerson from './components/MyPerson.vue';

export default {
  name: 'App',
  components: {
    MyFirstComponents,
    MyLifeCycle,
    MyPerson
  },
}
</script>
<style lang="">
  
</style>