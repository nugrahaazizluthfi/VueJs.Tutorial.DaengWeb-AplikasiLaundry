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
import Breadcrumb from "../../components/Breadcrumb.vue";
export default {
    name: "IndexCourier",
    components: {
        breadcrumb: Breadcrumb
    }
};
</script>

<style scoped></style>
