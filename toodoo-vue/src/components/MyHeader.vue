<template lang="">
    
    <ul>
        <li><a href="#">op 1</a></li>
        <li><a href="#">op 2</a></li>
        <li><a href="#">op 2</a></li>
        <li v-if="logado"><a href="www.github/Tallys-Aureliano">My github</a></li>
    </ul>

</template>

<script>
export default {
    name: "MyHeader",
    props: ["logado"],
    data() {
        return {

        }
    },
}
</script>
<style scoped>
ul {
    list-style: none;
    display: flex;
    background-color: chocolate;
}

li {
    margin: 10px;
}

a {
    color: rgb(84, 67, 92);
    text-decoration: double;
    transition: .5s;

}

a:hover {
    color: thistle;
}
</style>