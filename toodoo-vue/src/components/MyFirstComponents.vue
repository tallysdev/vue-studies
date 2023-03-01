<template>
    <div>
        <h2>Aureliano {{ nome }} e sou {{profissao}}</h2>
    </div>
</template>

<script>
export default {
    name: 'MyFirstComponents',
    data() {
        return {
            nome: "Dantas dos Santos",
            profissao: "Programandor FullStack"
        }
    },
}
</script>
<style scoped>

</style>