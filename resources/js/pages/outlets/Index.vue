<template>
    <div class="container">
        <section class="content-header">
            <h1>Manage Outlets</h1>
            <breadcrumb></breadcrumb>
        </section>
        <section class="content">
            <div class="row">
                <router-view></router-view>
            </div>
        </section>
    </div>
</template>

<script>
import Breadcrumb from "./../../components/Breadcrumbs.vue";
export default {
    name: "IndexOutlet",
    components: {
        breadcrumbs: Breadcrumb
    }
};
</script>

<style scoped></style>
