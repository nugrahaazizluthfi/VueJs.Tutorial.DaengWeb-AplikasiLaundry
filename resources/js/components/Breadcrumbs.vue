<template>
    <div class="breadcrumb">
        <li>
            <router-link :to="{ name: 'home' }">
                <i class="fa fa-dashboard"></i> Home
            </router-link>
        </li>
        <li class="active">{{ $route.meta.title }}</li>
    </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
