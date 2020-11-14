<template>
    <div>
        <app-header v-if="isAuth"></app-header>
        <div class="content-wrapper">
            <router-view></router-view>
        </div>
        <app-footer v-if="isAuth"></app-footer>
    </div>
</template>

<script>
import { mapState, mapGetters, mapMutations } from "vuex";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
    name: "App",
    computed: {
        ...mapState(["token"]),
        ...mapState(["isAuth"])
    },
    components: {
        "app-header": Header,
        "app-footer": Footer
    }
};
</script>

<style scoped></style>
