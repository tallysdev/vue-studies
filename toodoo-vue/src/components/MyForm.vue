<template lang="">
    <div>
        <form action="">
            <MyInput/>
            <MyInput/>
            <MySubmit/>
        </form>    
    </div>
</template>

<script>

import MyInput from './form/MyInput.vue';
import MySubmit from './form/MySubmit.vue';

export default {
    name:'MyForm',
    components: {
        MyInput,
        MySubmit
    },
    data() {
        return {
            
        }
    },
}
</script>
<style lang="">
    
</style>