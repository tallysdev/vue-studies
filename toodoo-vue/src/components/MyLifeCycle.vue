<template>
    <div>
        <h1>Meu nome é: {{ name }}</h1>
    </div>
</template>

<script>
export default {
    name: 'LifeCycle',
    data() {
        return {
            name: 'Nome ainda nao sei'
        }
    },
    created(){
        setTimeout(() => {
            this.name = "Jose"
        }, 1000);
        this.lifeCycle()
    },
    mounted() {
        this.name = "tallys"
    },
    methods: {
        lifeCycle(){
            console.log("executou")
        }
    },
}
</script>

<style scoped>
    
</style>