<script>
    import Layout from '../../Shared/Layout.vue';

    export default {
        props: ['title'],
        components: {
            Layout
        }
    }
</script>

<template>
    <Layout>
        <h1>Daftar {{ title }}</h1>
        <ol>
            <li>Kholid</li>
            <li>Kamali</li>
        </ol>
    </Layout>
</template>