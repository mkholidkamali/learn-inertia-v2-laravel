<script>
    export default {
        props: ['title']
    }
</script>

<template>
    <div class="mx-center text-center m-5">
        <h1>{{ title }}</h1>
        <Link href="/home">Home</Link>
    </div>
</template>