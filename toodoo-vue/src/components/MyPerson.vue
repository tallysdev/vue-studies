<template lang="">
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt dolores quas voluptates aperiam, labore consequatur ipsam {{ name }} blanditiis corporis assumenda, odit neque officia omnis esse. Asperiores ipsam repudiandae excepturi laboriosam ducimus?</p>
        <MyInfo/>
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
            name: "Tallys"
        }
    },

}
</script>
<style lang="">
    
</style>