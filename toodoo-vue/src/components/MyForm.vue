<template lang="">
    <div>
        <form action="" @MySubmit="enviarFormulario($event)">
            <input type="text" :v-model="name">
            <MyInput/>
            <MySubmit/>
        </form>    
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit deserunt, quae numquam nihil iste, vitae reprehenderit itaque sequi tempore beatae mollitia animi ea doloribus molestias. Incidunt perspiciatis cumque beatae iusto!</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia tempore quod illum odio id veritatis sed, aut minima, quisquam cupiditate nihil reiciendis quae porro magnam incidunt? Aliquam voluptas praesentium vero.</p>
    </div>
</template>

<script>

import MyInput from './form/MyInput.vue';
import MySubmit from './form/MySubmit.vue';

export default {
    name:'MyForm',
    components: {
        MyInput,
        MySubmit
    },
    methods: {
        enviarFormulario(e){
            e.preventDefault();

            const name = this.name;
            console.log(name);

            // Ajax
            
        }
    },
    data() {
        return {
            name: "tallys",
        }
    },
}
</script>
<style scoped>
    p {
        margin: 25px;
    }
</style>