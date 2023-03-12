<template lang="">
    <img :src="avatar" :alt="descricao ">
</template> 

<script>
export default {
    name: "MyPicture",
    data() {
        return {
            avatar: "favicon.ico",
            descricao: "minha foto",
        }
    },
}
</script>
<style lang="">
    
</style>