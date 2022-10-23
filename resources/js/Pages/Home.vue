<script>
    import Layout from '../Shared/Layout.vue';

    export default {
        components: {
            Layout
        },
        props: ['title']
    }
</script>

<template>
    <Layout title="Inertia - Laravel">
        <h1>{{ title }}</h1>
    </Layout>
</template>