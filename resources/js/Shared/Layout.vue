<template>
    <main>
        <header class="flex justify-around mt-4">
            <Link href="/home">Home</Link>
            <Link href="/about">About</Link>
            <Link href="/users">Users</Link>
        </header>
        <article class="mx-center text-center m-5">
            <hr>
            <slot />
            <hr>
        </article>
    </main>
    <footer>
        <p class="text-center">&copy; KholidKamali 2022</p>
    </footer>
</template>

<script>
import { Link } from '@inertiajs/inertia-vue3'

export default {
    components: {
        Link,
    },
    props: {
        title: String
    },
    watch: {
        title: {
            immediate: true,
            handler(title) {
                document.title = title;
            }
        }
    }
}
</script>