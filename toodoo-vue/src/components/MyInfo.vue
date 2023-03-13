<template lang="">
    <div>
        <button @click="showEmail"> {{textoB}}</button>
        <p class="paragrafo-pai">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque fugit dolore officiis illo, placeat doloribus laborum, voluptatem magni ullam odio repellat animi nemo? Totam rem quo rerum quia facere illo?</p>
        <p v-if="Work"> Está trabalhando</p>
        <p v-else> Não está trabalhando</p>
        <p v-show="email">tallysdev@gmail.com</p>
        <p>Para acessar o meu <a href="github" target="_blank">github</a> basta clicar aqui</p>
        <p>backend</p>
        <ul>
            <li v-for="(tecnology, index) in backend_tecnologies" v-bind:key="index">{{tecnology}}</li>
        </ul>
        <p>frontend</p>
        <ul>
            <li  v-for="tecnology in frontend_tecnologies" :key="tecnology.id">
                {{tecnology.language}}</li>
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
            backend_tecnologies: ["TypeScript","NodeJS","NestJS","ExpressJS"],
            frontend_tecnologies: [
                {id: 1, language: "JavaScript" },
                {id: 2, language: "HTML" },
                {id: 3, language: "CSS" },
            ]
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