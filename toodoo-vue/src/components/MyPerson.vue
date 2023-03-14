<template lang="">
    <div>
        <p class="teste">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt dolores quas voluptates aperiam, labore consequatur ipsam {{ name }} blanditiis corporis assumenda, odit neque officia omnis esse. Asperiores ipsam repudiandae excepturi laboriosam ducimus?</p>
        <MyInfo :compEmail="compEmail"/>
    </div>
</template>

<script>

import MyInfo from './MyInfo.vue';

export default {

    name: 'MyPerson',
    components: {
        MyInfo, 
    },
    data() {
        return {
            name: "Tallys",
            compEmail: "Tallysdev@gmail.com"
        }
    },

}
</script>
<style lang="">
    
</style>