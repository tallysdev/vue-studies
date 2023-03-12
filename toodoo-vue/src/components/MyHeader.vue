<template lang="">
    
    <ul>
        <li><a href="#">op 1</a></li>
        <li><a href="#">op 2</a></li>
        <li><a href="#">op 2</a></li>
    </ul>

</template>

<script>
export default {
    name: "MyHeader",
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