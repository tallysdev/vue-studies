<template>
    <div>
        <h2>Aureliano {{ nome }} e sou {{profissao}}</h2>
        <MyMultiplosEventos/>
        <MyReuse/>
        <MyReuse/>
        <MyReuse/>
        <MyReuse/>
        
    </div>
    
</template>

<script>

import MyMultiplosEventos from './MyMultiplosEventos.vue';
import MyReuse from './MyReuse.vue';

export default {
    name: 'MyFirstComponents',
    components: {
        MyMultiplosEventos,
        MyReuse,
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