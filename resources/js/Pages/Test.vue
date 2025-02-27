<script setup>
    import Layout from "../Layouts/MainLayout.vue";
    import {Head} from "@inertiajs/vue3";

    defineProps({
        age: Number
    })

    defineOptions({
        layout: Layout,
    })
</script>

<template>
    <Head>
        <title>Test</title>
        <meta name="description" content="This is the Test Page" />
    </Head>

    <div>
        <h3>Test</h3>
    </div>
</template>

