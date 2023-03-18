<template>
    <MyBanner/>
    <div class="main-container">
        <h1>Monte o seu Burger</h1>
        <MyBurgerForm/>
    </div>
</template>
<script>

import MyBanner from '@/components/MyBanner.vue';
import MyBurgerForm from '@/components/MyBurgerForm.vue';

export default {
    name:"MyHome",
    components: {
        MyBanner,
        MyBurgerForm,
    }
}
</script>
<style scoped>
    
</style>