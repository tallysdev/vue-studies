<template lang="">
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'MyBanner',

}
</script>

<style scoped>
    
    #main-banner {
        background-image: url(../../public/img/burger.jpg);
        background-position: 0 -250px; 
        background-size: cover;
        height: 600px;
        /* height: 500px; */
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: white;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }

</style>