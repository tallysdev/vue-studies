<template lang="">
  <MyHeader/>

  <div>
    <h1>Tallys</h1>
    <p class="paragrafo-pai">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestiae suscipit quaerat sed nihil quos esse magnam illo reprehenderit exercitationem vero, rerum inventore repellat magni fugit veritatis nemo, quam libero illum!</p>
  </div>
  <MyFirstComponents/>
  <MyLifeCycle/>
  <MyPerson/>

</template>

<script>

import MyFirstComponents from './components/MyFirstComponents.vue';
import MyLifeCycle from './components/MyLifeCycle.vue';
import MyPerson from './components/MyPerson.vue';
import MyHeader from './components/MyHeader.vue';

export default {
  name: 'App',
  components: {
    MyFirstComponents,
    MyLifeCycle,
    MyPerson,
    MyHeader,
  },
}
</script>

<style>
body {
  background-color: black;
  color: wheat;
}

a {
  color: forestgreen;
}

.teste {
  color: yellow;
}

.paragrafo-pai {
  color: aqua;
}
</style>