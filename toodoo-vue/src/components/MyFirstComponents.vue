<template>
    <div>
        <h2>Aureliano {{ nome }} e sou {{profissao}}</h2>
        <MyMultiplosEventos/>
    </div>
    
</template>

<script>

import MyMultiplosEventos from './MyMultiplosEventos.vue';

export default {
    name: 'MyFirstComponents',
    components: {
        MyMultiplosEventos,
    },
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