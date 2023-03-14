<template lang="">
    <img :src="avatar" :alt="descricao ">
    <MyChangeImage @mudar-img=" trocarImg"/>
</template> 

<script>

import MyChangeImage from './MyChangeImage.vue';

export default {
    name: "MyPicture",
    components: {
        MyChangeImage,
    },
    data() {
        return {
            avatar: "/favicon.ico",
            descricao: "minha foto",
        }
    },
    methods: {
        trocarImg() {
            this.avatar = "/coca-cola-logo-2007.jpg"
        },
    },
}
</script>
<style scoped>
    img {
        max-width: 100px;
        max-height: 50px;
    }
</style>