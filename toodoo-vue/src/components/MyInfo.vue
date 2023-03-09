<template lang="">
    <div>
        <p v-if="Work"> Está trabalhando</p>
        <p v-else> Não está trabalhando</p>
        <p v-show="email">tallysdev</p>
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
            Work : false,
            email: true,
        }
    },    
}
</script>
<style lang="">
    
</style>