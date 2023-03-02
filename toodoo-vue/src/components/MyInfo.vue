<template lang="">
    <div>
        <ul>
            <li>
                teste    
            </li>

            <li>
                teste 2
            </li>

            <li>
                teste 3
            </li>   
        </ul>

        <MyForm/>

    </div>
</template>

<script>

import MyForm from './MyForm.vue';

export default {
    name: 'MyInfo',
    components: {
        MyForm
    },
    data() {
        return {
        
        }
    },    
}
</script>
<style lang="">
    
</style>