<template>
    <section>
        <!-- <img class="curvy-bg" src="../assets/img/bg-curvy-desktop.svg" alt /> -->
        <main-header />
        <main-body />
        <main-footer />
    </section>
</template>

<script>
import mainHeader from "../components/main.header.vue"
import mainBody from "../components/main.body.vue"
import mainFooter from "../components/main.footer.vue"

export default {
    // props: [''],
    components: {
        mainHeader,
        mainBody,
        mainFooter,
    },
    created() { },
    data() {
        return {}
    },
    methods: {},
    computed: {},
    unmounted() { },
}
</script>