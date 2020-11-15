<template>
    <div class="container">
        <section class="content-header">
            <h1>Manage Outlets</h1>
            <breadcrumbs></breadcrumbs>
        </section>
        <section class="content">
            <div class="row">
                <router-view></router-view>
            </div>
        </section>
    </div>
</template>

<script>
import Breadcrumbs from "./../../components/Breadcrumbs.vue";
export default {
    name: "IndexOutlet",
    components: {
        breadcrumbs: Breadcrumbs
    }
};
</script>

<style scoped></style>
