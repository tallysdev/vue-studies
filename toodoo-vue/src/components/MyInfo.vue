<template lang="">
    <div>
        <button @click="showEmail"> {{textoB}}</button>
        <p v-if="Work"> Está trabalhando</p>
        <p v-else> Não está trabalhando</p>
        <p v-show="email">tallysdev@gmail.com</p>
        <p>Para acessar o meu <a href="github" target="_blank">github</a> basta clicar aqui</p>
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
        <MyPicture/>

    </div>
</template>

<script>

import MyForm from './MyForm.vue';
import MyPicture from './MyPicture.vue';

export default {
    name: 'MyInfo',
    components: {
        MyForm,
        MyPicture,
    },
    data() {
        return {
            Work : true,
            email: false,
            github: "www.github.com/Tallys-Aureliano",
            textoB: "Mostrar Email",
        }
    },
    methods: {
        showEmail() {
            this.email = !this.email
            this.Work = !this.Work
            if (!this.email) {
                this.textoB = "Mostrar Email"
            } else {
                this.textoB = "Esconder Email"
            }
        },
    },    
}
</script>
<style lang="">
    
</style>