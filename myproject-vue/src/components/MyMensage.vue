<template>
    <div class="mensagem-container">
        <p>{{ msg }}</p>
    </div>
</template>
<script>

export default {
    name: "MyMensage",
    props: {
        msg: String,
    },
    data() {
        return {
            
        }
    },    
}
</script>
<style scoped>
    .mensagem-container {
        color: #004085;
        /* text-align: center; */
        background-color: #CCE5FF;
        border: 2px solid #B8DAFF;
        border-radius: 5px;
        padding: 10ox;
        max-width: 400px;
        margin: 30px auto;
    }
</style>