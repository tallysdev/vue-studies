<template lang="">
    <div>
        <button @click="$emit('MudarImg')">trocar img</button> 
    </div>
</template>
<script>

export default {
    name: "MyChangeImage",
    emits: ['MudarImg'],
    data() {
        return {
            
        }
    },
    methods: {
        
    },
}
</script>
<style lang="">
    
</style>