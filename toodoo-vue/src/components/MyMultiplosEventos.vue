<template lang="">
    <div>
        <button @click="primeiro(txt1,$event), segundo(txt2,$event),terceiro()">Ativar MyMultiplos Eventos</button>
        <p>{{multiplosEventos}}</p>
    </div>
</template>
<script>

export default {
    name: "MyMultiplosEventos",
    data() {
        return {
            multiplosEventos: "",
            txt1: "Priemeiro evento",
            txt2: "Segundo evento"
        }
    },
    methods: {
        // eslint-disable-next-line no-unused-vars
        primeiro(txt, e) {
            this.multiplosEventos = txt
        },
        // eslint-disable-next-line no-unused-vars
        segundo(txt, e) {
            setTimeout(() => this.multiplosEventos = txt, 500)
        },
        terceiro() {
            setTimeout(() => this.multiplosEventos = "", 1500)

        },
    },
}
</script>
<style scoped>
div {
    margin: 100px;
}
</style>