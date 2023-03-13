<template lang="">
    <div>
        <button @click="ativar">Clique aqui</button>
        <span v-show="ativou"> Ativado!</span>
    </div>
</template>

<script>
export default {
    name:"MyReuse",
    data() {
        return {
            ativou: true,
        }
    },
    methods: {
        ativar(){
            this.ativou = !this.ativou
        }
    },
}
</script>
<style scoped>

</style>