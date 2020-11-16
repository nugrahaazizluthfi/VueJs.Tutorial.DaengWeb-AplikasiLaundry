<template>
    <div class="container">
        <div class="content-header">
            <h1>Manage Couriers</h1>
            <breadcrumb></breadcrumb>
        </div>

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
    name: "IndexCourier",
    components: {
        breadcrumb: Breadcrumbs
    }
};
</script>

<style scoped></style>
