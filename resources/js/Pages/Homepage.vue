<script setup>
    import Layout from "../Layouts/MainLayout.vue";
    import { Head } from "@inertiajs/vue3";

    defineOptions({
        layout: Layout,
    })
</script>

<template>
    <Head>
        <title>HomePage</title>
        <meta name="description" content="This is the Homepage" />
    </Head>

    <div>
        <h3>Homepage</h3>
    </div>
</template>

